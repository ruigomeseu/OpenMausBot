# Desktop viewer PR evidence

Captured from the isolated viewer fixture at source commit 4fa37d382ff3802e0ca9e112e32e0dcbf55e1f8c, based on upstream 104fd17b8f7767e71ba3cf40f27f9c6279b507bd.

- Before: browser reproduction of a loopback VNC URL pointing at an unused client port; no live desktop or user data is involved.
- After: the production viewer connected to the fixture's synthetic 16x16 RFB desktop. Its red pixels are intentionally artificial; blank regions in phone captures reflect the synthetic desktop's limited repaint behavior.
- Video: a short recording of the fixture exercising sidebar collapse/expansion and fullscreen.

The fixture uses a disposable home, fake Docker/SSH executables and a synthetic RFB server. Screenshots and video contain no real VM desktop, user account data or credentials.
