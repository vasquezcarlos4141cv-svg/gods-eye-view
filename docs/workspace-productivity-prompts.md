# Workspace Productivity Prompts

Copy-paste prompts for Gemini in Google Workspace (Drive, Sheets) to inventory
files, track time spent per project, and keep a log of LLM prompts.

## 1. Google Drive inventory and file breakdown

Run these in Gemini on Google Drive, or from inside Google Sheets.

**List and categorize files**

> Scan my Google Drive and list all files (excluding Google Sheets/Excel). For
> each file, summarize what it is, its file format, size, and the folder
> location.

**A-to-Z inventory by file type and size**

> Create an A-to-Z inventory table of all non-spreadsheet files in my Drive,
> including columns for File Name, Folder, File Type, File Size, and Last
> Modified Date.

## 2. Project time and effort tracking

**Map files to time spent**

> Cross-reference the files in my Google Drive with my 'Project Time Tracker'
> sheet. Match each project name to its corresponding drive files and show total
> hours spent on each.

**Summarize time by file or project**

> Summarize total time logged per project and provide an average time spent per
> task across all files.

## 3. Prompt log and LLM prompt tracking

**Create a prompt tracker table**

> Create a prompt tracking table with columns for: Prompt ID, Topic/Project,
> Platform/LLM Used, Exact Prompt Text, Key Output Summary, Date Used, and Tags.

**Organize and structure prompt history**

> Organize my prompt history into categories (e.g., Data Analysis, Writing,
> Setup, Review) and add a column to rate or note the effectiveness of each
> prompt.

### Suggested prompt tracker columns

| Column             | Example                               |
| ------------------ | ------------------------------------- |
| Prompt ID          | `P-0001`                              |
| Topic/Project      | God's Eye View – data sources         |
| Platform/LLM Used  | Gemini / Claude                       |
| Exact Prompt Text  | _full prompt as sent_                 |
| Key Output Summary | One-line summary of the result        |
| Date Used          | 2026-10-11                            |
| Tags               | `setup`, `review`                     |
| Category           | Data Analysis / Writing / Setup / ... |
| Effectiveness      | 1–5 rating or short note              |

## Tips

- Name the time-tracking sheet exactly `Project Time Tracker` so the
  cross-reference prompt can find it.
- Use the same project names in the tracker sheet as in your Drive folder names;
  matching is far more reliable that way.
- Gemini's Drive answers reflect what it can index; verify file sizes and
  dates against Drive's own details pane before relying on them.
