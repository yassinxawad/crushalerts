# CrushAlerts — TikTok Developer Submission

## App
- Name: CrushAlerts
- Developer/organisation: 心动科技 (Xīndòng Kējì)
- Website: https://yassinxawad.github.io/crushalerts/
- Privacy Policy: https://yassinxawad.github.io/crushalerts/privacy.html
- Terms: https://yassinxawad.github.io/crushalerts/terms.html
- Support: https://yassinxawad.github.io/crushalerts/support.html
- Support email: Yassinxawad@icloud.com

## Product purpose
CrushAlerts is an iOS utility that lets an authorised user connect a supported TikTok Business account, select one TikTok Business Messaging conversation, and receive an Apple push notification when supported messaging event data indicates new activity.

## Data handling
The intended architecture minimises server-side retention. Full message content is intended to remain on the user's device. The service may process the identifiers and authorisation/event data needed to identify the selected conversation and deliver notifications.

## Current API configuration status
- Redirect URL: Not configured yet
- Webhook URL: Not configured yet
- TikTok Business Messaging integration: Planned
- Final TikTok scopes: Not selected yet

Do not claim API access or scopes in a submission until TikTok has granted them and the final implementation uses them.

## Demo video plan
1. Launch CrushAlerts.
2. Show the onboarding explanation.
3. Start the TikTok authorisation flow.
4. Complete authorisation with an eligible test account.
5. Select the supported conversation.
6. Show the notification/event flow.
7. Show Settings → Account → Disconnect And Reset.
8. Demonstrate that local app data is reset.

## Security
- Never publish TikTok client secrets.
- Never put access tokens in the website, README, screenshots or public repository.
- Verify webhook signatures before processing webhook events.
- Keep the minimum scopes necessary.
- Do not collect or retain data that is not required for the feature.

## URL
GitHub Pages project sites use the repository path after the account domain, so this project's intended public URL is:
https://yassinxawad.github.io/crushalerts/
