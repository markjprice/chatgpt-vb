# ChatGPT Add-ins for Word, Excel, and PowerPoint (Bonus Content)

*Companion material for* ChatGPT Visual Bible, *Book 2. This bonus section covers a feature that requires a ChatGPT Business or Enterprise account, so it isn't included in the print book. Information verified as of August 2026 — always check OpenAI's current help documentation before relying on install steps, since add-in features change without notice.*

## The idea in one sentence

Instead of drafting in ChatGPT and copying the result into Word, Excel, or PowerPoint, you can add ChatGPT as a side panel inside each application and draft, rewrite, and insert text without switching windows.

## Two ways to get it

**OpenAI's own ChatGPT app for Office.** This is the official add-in, published through Microsoft AppSource. It requires a **ChatGPT Business or Enterprise** account and adds a matching ChatGPT pane to Word, Excel, and PowerPoint. In a managed organization, an administrator typically needs to deploy it through the Microsoft 365 Admin Center rather than letting individual users install it.

**Third-party add-ins.** Listings such as "GPT for Word" or "ChatGPT for Excel and Word" are also available in AppSource. These work on any ChatGPT plan, including Free and Plus, because they call the OpenAI API directly using your own API key rather than your ChatGPT account. You pay for API usage separately, and the add-in publisher (not OpenAI) is responsible for how your text is handled, so review its privacy policy before pasting anything confidential through it.

## Installing the add-in (general steps)

1. Open Word, Excel, or PowerPoint, signed in with your Microsoft 365 account.
2. In the ribbon, select **Home → Add-ins** (or **Insert → Get Add-ins** on some versions).
3. Search for **ChatGPT** or the specific add-in name.
4. Select **Add**, then complete sign-in: your ChatGPT Business or Enterprise account for the official add-in, or your OpenAI API key for a third-party add-in.
5. Pin the add-in to the ribbon for quick access.

If **Add-ins** is greyed out or the install fails, your organization has likely restricted user-installed add-ins. Ask an administrator to deploy it centrally through **Microsoft 365 Admin Center → Integrated Apps**.

## What you can do in each app

### Word
- Draft a section directly from a brief without leaving the document.
- Rewrite a selected paragraph in a specific tone, then insert the result at your cursor.
- Summarize a long document that's already open in Word, without uploading it anywhere else first.

### Excel
- Describe a calculation in plain language and get a working formula back, such as `SUMIFS` or `XLOOKUP`, instead of writing it yourself.
- Ask ChatGPT to explain what an unfamiliar formula in an inherited spreadsheet actually does.
- Select a messy column and ask for cleanup or standardization suggestions without leaving the sheet.

### PowerPoint
- Draft slide titles and speaker notes from a brief you have open elsewhere.
- Rewrite a dense, text-heavy slide as a shorter, more visual version.
- Generate alt text for an image already on a slide, to improve accessibility.

## Why Outlook is different

Word, Excel, and PowerPoint get an add-in pane that lives inside the application. Outlook doesn't currently work the same way. Instead, Outlook is accessed as a **connected app from within ChatGPT** — the same mechanism used for OneDrive, SharePoint, Teams, and Calendar, covered in Chapter 2.8 of the print book (Add Plugins, Apps, and Skills). You connect Outlook in ChatGPT's Plugin Directory, then work from ChatGPT itself to search, summarize, or draft replies from your mailbox, rather than opening a ChatGPT panel inside Outlook.

## Good to know before you install anything

- The official add-in only works with paid Business or Enterprise ChatGPT accounts. If your organization uses Plus or Free, you either need a plan upgrade, IT approval, or a third-party add-in with your own API key.
- Whatever path you use, the same rules from Chapter 2.1 of the print book still apply: check your employer's AI policy, keep confidential and regulated data out unless your organization has approved that use, and verify anything the add-in generates before you rely on it.
- Add-ins operate prompt by prompt, on the document or sheet you have open. They don't watch a folder or inbox and act automatically — that's a different category of tool (automation and scheduled tasks), covered in Book 3.
