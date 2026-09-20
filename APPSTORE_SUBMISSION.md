# CrushAlerts — App Store Submission

## Confirmed project information
- App: CrushAlerts
- Developer: Yassin Safwat Awad
- Organisation/project: 心动科技 (Xīndòng Kējì)
- Website: https://yassinxawad.github.io/crushalerts/
- Privacy Policy: https://yassinxawad.github.io/crushalerts/privacy.html
- Terms: https://yassinxawad.github.io/crushalerts/terms.html
- Support: https://yassinxawad.github.io/crushalerts/support.html
- Disconnect & Reset: https://yassinxawad.github.io/crushalerts/delete-account.html
- Support email: Yassinxawad@icloud.com
- Address: Not published
- Subtitle: Alerts for selected chats
- Primary category: Utilities
- Secondary category: Social Networking (only if the final app functionality fits)
- Account model: No separate CrushAlerts account currently planned.
- Local reset: Settings → Account → Disconnect And Reset

## Suggested description
CrushAlerts helps users stay aware of new activity in one selected TikTok Business Messaging conversation. Users connect an eligible TikTok account through the supported authorisation flow, select one conversation, and receive a push notification when supported messaging data indicates new activity.

Message information is intended to remain local on the user's device rather than being stored as full message content on a CrushAlerts server. Notification timing depends on third-party processing, network conditions and Apple notification delivery.

## Keywords
alerts,chat,notifications,messages,crush

## Privacy answers — verify against the final binary
The app may process TikTok account identifiers, authorisation information, conversation/event identifiers and push-notification information. Full message content is intended to remain local on the device.

Do not submit these declarations until they have been checked against the final implementation and all SDKs.

## Account deletion / reset
The current planned flow is:
Settings → Account → Disconnect And Reset

This is a disconnect/reset flow because the app does not currently create a separate CrushAlerts account. Ensure the final implementation matches this documentation before submission.

## App Review notes draft
CrushAlerts is a notification utility for supported TikTok Business Messaging functionality. The reviewer can connect an eligible TikTok account through the in-app authorisation flow, select one conversation, and observe notification handling for supported messaging events.

The app does not require a separate CrushAlerts account. Local data can be cleared through Settings → Account → Disconnect And Reset.

If TikTok API access requires a sandbox or test account, provide the reviewer with the appropriate credentials/capabilities through App Store Connect review notes without exposing secrets in public documentation.

## Important
This document is a submission preparation document, not a guarantee of Apple or TikTok approval. The final metadata must match the actual binary and integrations.
