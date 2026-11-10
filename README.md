# Tag Print for Windows

Official binary downloads for the LiveTag local printing assistant. POS source code is not published here.

## Windows Preview v0.1.0

Requires Windows 10/11 x64 and the printer manufacturer's Windows driver. Supports the existing 80mm / 576-dot receipt pipeline. Runtime is included; no separate Node installation is required.

1. Download the installer from Releases.
2. Install Tag Print, choose an installed printer, then Save & start.
3. In the updated LiveTag POS account menu (Printers & devices), or KDS Printer settings, choose Connect Tag Print.
4. Confirm the website and printer in the desktop approval window. No manual pairing code is needed.

Closing the window keeps the helper running in the tray. Sign-in startup is optional. Each Windows computer/browser pairs independently. Use Reset browser connections to revoke all browser approvals.

This is an **unsigned preview**, pending physical printer acceptance testing. Validate on a test computer before merchant rollout. The new connection UI requires the corresponding LiveTag frontend update. Packaged builds authorize only the official https://pos.mylivetag.app website. Development localhost use requires the developer build.

Exit the old LiveTag Print Service before starting Tag Print, because both use the same local port. Android support is separate. Automatic printing is not deduplicated across multiple computers; designate the intended automatic-print terminal.

SHA256SUMS.txt accompanies every published installer. A queue-submitted result is not a guarantee of physical paper output. Interrupted or uncertain jobs are not automatically replayed.