Emacs needs access to GnuTLS dll files ever since melpa.org switched to TLS.

http://xn--9dbdkw.se/diary/how_to_enable_GnuTLS_for_Emacs_24_on_Windows/index.en.html

GnuTLS archive for Windows is available at http://sourceforge.net/projects/ezwinports/files/.
Download `gnutls-3.3.11-w32-bin.zip` (or newer, if available) and extract all `*.dll` files
from the bin subdirectory to the Emacs' installation `bin` directory.

Restart Emacs and Prelude should be able to download all the packages from melpa.org.

GnuTLS theoretically requires configuration of trust certificates but I did not find it
to be the case on my system (Windows 10).
