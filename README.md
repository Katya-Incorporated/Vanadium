Vanadium is a privacy and security hardened variant of Chromium providing the WebView (used by
other apps to render web content) and standard browser for [Katya ® 👽 System](https://katyasystem.site/).
It depends on hardening and compatibility fixes in Katya ® 👽 System rather than reinventing the wheel
inside Vanadium. For example, Katya ® 👽 System already provides a hardened malloc implementation so
there's no need for Vanadium to replace it. Similarly, it can deploy security features causing
breakage on other operating systems due to the ability to fix compatibility problems in the OS.
