# Ubuntu Sever Development Summary
This repository is used by the Canonical Server team to develop the weekly
development summary that is sent out to the community as a whole. This summary
is used to communicate accomplishments and progress made by the server team
over the previous week.

## Template
The template is a starter to generating the weekly summary. This is used to
allow whoever is working on the summary to focus on content and not style.

## Instructions
Below is a list of steps to generate the complete summary:

1. Template
  - Copy the template.md file to doc string
  - `cp template.md doc/$(date +'%Y-%m-%d').md`
2. Uploads
  - Download and run the [upload report](https://raw.githubusercontent.com/canonical-server/metrics/master/metrics/upload_report.py)
  - Use the preivous Friday as the input date
3. Triage Queue
  - Login to the team KPI and grab the three values under Bug Triage.
4. IRC Meeting
  - Get the link to the latest meeting from [Meetingology](https://ubottu.com/meetingology/logs/ubuntu-meeting/)
5. cloud-init and curtin
  - Review the Trello board done column
  - Summarize any done cards
6. Ubuntu Server
  - Review the Trello board done column
  - Summarize any done cards
7. Review
  - Send out a link to the draft for review to the team
