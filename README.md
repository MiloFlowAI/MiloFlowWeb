# MiloFlow

MiloFlow is an iPhone-first personal AI memory workspace. Talk to Milo by voice
or text, turn conversations into notes and action items, search your own local
vault, and keep useful context available for future conversations.

MiloFlow is designed for people who want the ease of talking to an assistant
without giving up ownership of their notes, reminders, and work records.

## What MiloFlow Helps With

- Capture thoughts, meetings, and planning conversations before they disappear.
- Turn voice conversations into summaries, decisions, requirements, and action
  items.
- Search local records and an optional Markdown vault when you want Milo to
  remember past work.
- Create reminders and connect them with Apple Reminders.
- Use Incognito mode for conversations you do not want folded into memory.
- Export local data when you need a backup or handoff.

## Workspaces

MiloFlow includes several places to think:

- **Milo chat** for everyday questions, reflection, voice, web requests, vault
  search, and quick follow-through.
- **Projects** for plans, requirements, decisions, summaries, and action items.
- **Journal** for reflections, summaries, and personal follow-up.
- **Discussions** for meetings and longer conversations that need notes and next
  steps.

## Model Options

MiloFlow lets you choose the model path that fits the moment:

- **Local Gemma** runs on device when local assets are installed. It is useful for
  private chat, offline-friendly thinking, and everyday reflection.
- **Gemini Cloud** uses your own Gemini API key for cloud chat and typed or
  spoken turns.
- **Gemini Live** supports realtime voice, interruptions, transcripts, and tools.
  Pro uses your Gemini API key. Max can use hosted Gemini first.

## Plans

Pricing may vary by App Store region.

### Free

For private chat and local memory basics.

- Regular Milo and Incognito Milo
- Local Gemma when assets are installed
- Gemini Cloud with your own API key
- Local vault memory search
- Milo reminders and Apple Reminders linking

### Pro

For workspaces with your own Gemini key.

- $6.99 per month
- $59.99 yearly option available
- Project, Journal, and Discussion workspaces
- Gemini Live realtime voice with your own key
- Apple Watch remote voice control
- Workspace summaries and action items
- Workspace export
- Advanced live memory and tools using your key

### Max

For hosted Gemini without API-key setup.

- $16.99 per month
- $149.99 yearly option available
- Everything in Pro
- Hosted Gemini without API-key setup
- 150 hosted Live minutes per month
- 1,000 hosted text and tool actions per month
- 100 hosted web-search answers per month
- Bring your own Gemini API key anytime as a fallback

## Privacy And Data Ownership

MiloFlow is built around local records and user control.

- Your local app data is the source of truth.
- You can use a readable Markdown vault in a folder you choose.
- Milo can search your vault only when you ask or when the selected workflow uses
  memory.
- Incognito mode is available for conversations you do not want included in
  memory.
- You can refresh notes, delete the local index, forget the vault folder, and
  export a SQLite backup.

Cloud features depend on the model path you choose. Pro cloud usage is billed by
Google through the Gemini API key you provide. Max includes hosted Gemini usage
up to monthly limits.

## Set Up A Markdown Vault

The Markdown vault is optional, but it is the easiest way to keep readable Milo
notes in a folder you own. It works well with iCloud Drive and Obsidian.

Recommended setup:

1. Create an iCloud Obsidian vault named `MiloFlow`.
2. Open the Files app and confirm the folder appears at
   `iCloud Drive/Obsidian/MiloFlow`.
3. In MiloFlow, open **AI Settings**.
4. Open **Knowledge Base**.
5. Turn on **Sync Markdown Vault**.
6. Choose the `MiloFlow` vault folder.
7. Tap **Backfill Vault Now** to write your current readable notes into the
   vault.

After setup, MiloFlow can mirror readable records into the vault and search
those notes when memory or vault search is enabled. If search results look stale,
refresh or rebuild the vault index from Knowledge Base settings.

The vault is a readable mirror, not a full app backup. Use **AI Settings** ->
**Data Backup** -> **Export SQLite Backup** when you need a restorable app
backup. If a vault is selected, MiloFlow saves SQLite backups into the vault
`Backups/` folder.

## TestFlight

MiloFlow is currently iPhone-first and available by TestFlight request.

To request access, email:

```text
admin@miloflow.ai
```

Helpful details to include:

- Your iPhone model and iOS version
- Whether you want to test Free, Pro, or Max
- Whether you plan to use your own Gemini API key
- Any workflow you especially want to test, such as projects, journaling,
  discussions, reminders, or realtime voice

## Support

For support, bug reports, privacy questions, account questions, or TestFlight
access, contact:

```text
admin@miloflow.ai
```

You can also use:

- [MiloFlow website](https://miloflow.ai)
- [Support page](https://miloflow.ai/support.html)
- [Privacy notes](https://miloflow.ai/privacy.html)

## Notes For Testers

- TestFlight purchases use Apple sandbox billing and should not charge real
  money.
- Sandbox subscriptions renew faster than real App Store subscriptions.
- Real App Store subscriptions renew on the normal monthly or yearly schedule.
- Subscription changes, downgrades, and cancellations are handled through your
  Apple App Store account.
