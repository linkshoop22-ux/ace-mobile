ACE MOBILE — V1 PWA PACKAGE

WHAT THIS BUILD DOES
- Mobile-first ACE dashboard based on your existing standalone ACE browser build.
- Existing local-browser AI model loader, voice input/output, animated core, and optional local vision controls.
- Vision controls are collapsed by default.
- Prefers an installed en-GB George voice when the browser offers one; otherwise uses the closest available British English voice.
- No paid AI API or API key is embedded.

WHAT IS NOT CONNECTED YET
- Gmail is not connected. Gmail OAuth setup is required before ACE can read or send mail.
- SMS is not connected.
- Telephone calling is not connected. The current voice mode is an in-app browser conversation, not a carrier phone call.
- The AI model must download on first use and requires internet for the download. Inference is intended to run on-device when the iPhone browser supports it.

INSTALLATION REQUIREMENT
This package must be hosted on an HTTPS website before iPhone Safari can install it as a Home Screen web app and reliably grant microphone/camera access. The package contains no private keys or account credentials. Do not add passwords or API secrets to index.html.

FREE-COST NOTE
The static app package itself is free. Browser speech recognition availability and local model compatibility depend on iOS Safari. Gmail API standard usage is documented by Google as having no additional cost within its published limits, but Google notes that quota/billing terms may change; therefore do not enable billing or use a paid service if the strict zero-cost requirement is absolute.
