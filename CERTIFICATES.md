# Certificates and licenses — status

This file records what exists in GitHub versus what still requires owner authorization on vendor portals.

## Completed in this repository
- MIT `LICENSE` on `pointgoddesscc-sketch/orgsuite-meta-developers`
- Public privacy policy page for Meta App Review (`/privacy.html`)

## Existing OrgSuite certificate guidance repos (no private keys stored)
- Apple / platform beta: https://github.com/pointgoddesscc-sketch/orgsuite-beta-developer-certificate
- Google Play / Google Cloud: https://github.com/pointgoddesscc-sketch/orgsuite-google-developer-certificate
- iOS third-party notices: https://github.com/pointgoddesscc-sketch/orgsuite-ios-licenses-acknowledgements
- Facebook third-party notices: https://github.com/pointgoddesscc-sketch/orgsuite-facebook-third-party-notices

## TLS certificate
Vercel issues and renews HTTPS certificates for `*.vercel.app` automatically after a successful deploy. That is a Vercel TLS cert, not a Meta or Apple developer certificate.

## Requires Authorization (owner login — cannot be completed by this connector)
- Create the Meta app at https://developers.facebook.com/apps/creation/
- Register as a Meta developer at https://developers.facebook.com/async/registration
- Business Verification in Meta Business Suite
- App Review Advanced Access submission
- Apple Developer certificate / provisioning profiles
- Google Play signing key / Play Console enrollment
- GitHub commit-signing GPG/SSH key on the owner device
