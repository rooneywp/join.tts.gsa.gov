---
################################################################################
#                                                                              #
# INSTRUCTIONS                                                                 #
#                                                                              #
# -----------------------------------------------------------------------------#
# If you are editing this file on GitHub, first make sure you are creating a   #
# new file, and are not editing the template file! To create a new file, go to #
# https://github.com/18F/join.tts.gsa.gov/new/main in your browser.            #
#                                                                              #
# On the new file page, you can paste in the contents of the template file.    #
# Also be sure to type in a filename in the small textbox above the file body  #
# box. You will see the text join.tts.gsa.gov / [ Name your file ...] in main. #
# Type your filename into that box.                                            #
#                                                                              #
# NOTE ABOUTE FILENAMES: Your filename should be descriptive about the job     #
# posting that you're creating, and it MUST end with ".md". Don't stress out   #
# about filenames too much, though. They are used for the URL, which can help  #
# people make sure they're on the right page, but most users will probably not #
# notice the URL. Instead, try to make it meaningful to you and others on the  #
# Talent Team so you can find it easily in the future if you need to edit it.  #
#                                                                              #
# For example, if you are posting a job for a content designer, you might      #
# choose names like:                                                           #
#                                                                              #
#    tts-content-designer-2023.md                                              #
#    login-content-designer-2023.md                                            #
#    content-designer-2023.md                                                  #
#    content-designer-june-2023.md                                             #
#                                                                              #
# For the rest of the file, follow the directions as you go, but here are a    #
# couple more tips to help you as you work:                                    #
#                                                                              #
# You are currently inside the portion of the document called "frontmatter."   #
# The frontmatter is the part that starts with just "---" on the first line    #
# and ends with another line that only contains "---" (further down). This     #
# part of the document is not DIRECTLY shown to the user. Instead, this is     #
# where you can set data that will be shown to the user in other parts of the  #
# page, or data that is used to configure how the page is displayed. For       #
# example, the opens and closes dates are set in the frontmatter, but they     #
# will never be shown to the user the way you type them in. Instead, they are  #
# used to determine whether the posting is upcoming, open, or closed, and they #
# will be turned into more human-friendly text when they are displayed.        #
#                                                                              #
# Within this frontmatter block, lines that begin with a hash (#) symbol are   #
# comments. They do not contribute to the web page at all, but they are a nice #
# way of explaining what the data in the frontmatter is. It is okay to delete  #
# these comments when you are done, and it is also okay to leave them if they  #
# might be helpful when editing the page later.                                #
#                                                                              #
# The parts you need to fill out are marked with five red triangles above them #
# like this:                                                                   #
#🔻🔻🔻🔻🔻                                                                   #
#                                                                              #
# After the frontmatter, the rest of the document is in a special version of   #
# Markdown used by the website builder. You will see comments in that section  #
# as well, but they will look like this:                                       #
#                                                                              #
#    {% comment ----------------------------------------------------------- %} #
#    The contents in between these two lines are comments and do not           #
#    contribute to the web page.                                               #
#    {% endcomment -------------------------------------------------------- %} #
#                                                                              #
# It is safe to remove the Markdown comments as well.                          #
#                                                                              #
################################################################################

# This is the position title and the org that is doing the hiring. Please format
# your title as "Org: Position Title" (in quotes!). The organization should be
# a full name rather than an acronym. For example:
#   - U.S. Digital Corps, not USDC
#   - Presidential Innovation Fellows, not PIF
#
# NOTE: Be sure to leave the "title: " part at the beginning! These line
# headings are how the site builder knows what the data is. For the rest of the
# frontmatter, please be careful not to delete the headings!
#🔻🔻🔻🔻🔻
title: "Content Update Test Position"

# Put the opening and closing dates of your posting here, if you have them. The
# values you set here will be turned into user-friendly text in other parts of
# this post. Setting it here means you won't have to copy it over and over.
#
# These dates MUST be formatted as YYYY-MM-DD, where month and day are 2-digits.
# If the month number or day of the month are less than 10, add a 0 to the
# front (eg, May would be 05 instead of just 5). This is the only format the
# site builder automatically understands. Anything else will not be understood
# as a date.
#🔻🔻🔻🔻🔻
opens: 2024-02-01
closes: 2024-02-22
# These dates are also used to determine whether a position is upcoming, open,
# or closed. Here's how we decide:
#
# The job is upcoming if:
#   opens is empty OR
#   opens is in the future
#
# The job is open if:
#   opens is in the past OR
#   closes is in the future
#
# The job is closed if:
#   closes is in the past
#
# If either opens or closes is empty, missing, or not a date, the position is
# considered to be upcoming.

# If the position can also close when the maximum number of applications are
# received, include the maximum number of applications here. Remove this line
# or set the value to 0 if the job does not have an application cap.
#🔻🔻🔻🔻🔻
max applications: 0

# Put the GS grade this position is being advertised at. For SES positions, set
# the level to 20.
#🔻🔻🔻🔻🔻
gs: 15
# The information you put here will be used to automatically pull salary range
# information.
#
# ⚠️⚠️⚠️ IMPORTANT NOTE: The automatic salary ranges are based on 100% remote
# positions and use the lowest and highest locality areas. If this position is
# not 100% remote, you will need to delete the automatic salary range and input
# it yourself down below. Look for 💰💰💰 to indicate where to do that.
#
# The salary range data is stored in this file:
#
#   _data/pay_ranges.yml
#
# The data file will need to be updated each year to reflect any pay changes.

# List key objectives here. Key objectives and sub-bullets will be displayed in
# the order they are listed here. You do not need to include key objective
# numbers. They will be added automatically.
#
# Each key objective starts on a new line and must start with a dash. It does
# not need to include a number at the beginning. A key objective can be spread
# across multiple lines if you want.
#
# To add sub-bullets to your key objective, add a new line below the key
# objective and indent it with spaces. (The number of spaces does not matter, as
# long as it is more than one). Then, add a dash and your sub-bullet.
# Sub-bullets can also take up multiple lines as long as all of the lines are
# indented the same amount so they line up.
#
# The placeholder information below shows an example of how to format the key
# objectives. This example indents sub-bullets with two spaces:
#🔻🔻🔻🔻🔻
key objectives:
  - You will create more scalable and automated people operations processes,
    tools and systems for TTS
    - Oversee functions including TTS capacity management, performance
      management, employee travel, events, training and conference request,
      micropurchases, organizational audits (including OGE450), employee
      onboarding and offboarding, telework and full time telework agreements,
      career progression framework, timekeeping, and non recruit personnel
      action requests.
    - Analyze implementation of innovations in people operations operational
      matters, ensuring that TTS continues to develop and employ best in
      industry practices.
    - Build automated tools to automate flow of talent data and work systems;
      create custom tools in Google environment using custom scripts, formulas,
      pivot tables (i.e. employee travel estimator, newcomer tracker and event
      and training dashboards).
    - Mitigate employee questions and confusion by creating custom process
      guides to enable employees to more easily navigate complicated and complex
      processes including creating and updating telework agreements, preparing
      for employee offboarding and creating performance plans.

  - You will provide coaching, mentorship, and professional development
    opportunities; support employee wellbeing of People Operations team
    - Create a work environment that fosters trust, respect, and collaboration,
      since the best work comes from including diverse skill sets and
      backgrounds on the project. Uphold TTS values of inclusion, integrity,
      and impact.
    - Steward the team’s professional development, including identification of
      appropriate training, developmental assignments, and/or details.
      Incorporate equity and inclusion into plans for staff development,
      retention, training, speaking events, and experiential learning
      opportunities.
    - Encourage teamwork and a collaborative approach to problem solving.
    - Promote transparency in how decisions are made. Regularly include others
      in planning and decision-making.
    - Provide coaching, mentoring, and sponsorship to others in the
      organization, tailoring approaches to the needs of the individual. Work
      with individuals to identify and develop their strengths, helping team
      members pursue opportunities that enhance their talents.

  - You will establish trusting relationships with the TTS team and develop a
    deep understanding of people-related resources, policies, and best practices
    that impact their team members
    - Embody the spirit of customer service and genuinely engage with all
      members of TTS.
    - Maintain consistent lines of communication with leaders, guilds, and
      affinity groups to understand the problems and challenges facing their
      members and partners.
    - Navigate complex bureaucracy, build coalitions, and lead stakeholders with
      disparate views through change.
    - Promote fairness and equity and provide guidance to stakeholders that
      support this.

# If there are any info sessions associated with this position, list them here.
# Each info session needs three pieces of information: the link, the date, and
# the time. See the placeholder below for an example of how to add an info
# session. If the position does not have any info sessions, you can just delete
# the lines that begin with spaces.
#
# IMPORTANT: The date MUST be formatted as YYYY-MM-DD, where the month and day
# are TWO digits. If the month or day is less than 10, add a zero to the front.
# The date is used to sort the info sessions on the page so they are shown
# nearest to furthest. Only info sessions schedule for the future will be shown.
#🔻🔻🔻🔻🔻
info sessions:
  - link: https://www.eventbrite.com/...
    date: 2023-02-13
    time: 1:30-2:30pm ET (10:30am -11:30am PT)

# Put the link applicants need to use to apply for this position here. This link
# will be used for the "Click here to apply" button at the bottom of the
# position page.
#🔻🔻🔻🔻🔻
application link: https://usajobs.gov/job/apply/whatever
# This is the end of the frontmatter. After this line is Markdown.
---

{% comment ------------------------------------------------------------------ %}
If you want to include a closed/upcoming/open alert at the top of your page,
leave the following line. The status of the position will be determined by the
opens/closes dates at the top of this document

If you do not want the closed/upcoming/open alert, delete the line below that
says {% include job/status_alert.html %}
🔻🔻🔻🔻🔻
{% endcomment --------------------------------------------------------------- %}

{% include job/status_alert.html %}

## Basic information

Open to U.S. citizens or nationals (residents of American Samoa and Swains
Island). Subject to background check. Full information available on USAJOBS.

**Supervisory status:** Supervisory

**Job title:** {{ page.title }}

{% comment %}🔻🔻🔻🔻🔻{% endcomment %}
**Official title in USAJOBS:**

{% comment %}🔻🔻🔻🔻🔻{% endcomment %}
**Number of vacancies:** 1

{% comment %}🔻🔻🔻🔻🔻{% endcomment %}
**Location:** Anywhere in the U.S. (remote)

{% comment ------------------------------------------------------------------ %}
💰💰💰
The salary range for the job can be populated automatically based on the GS
grade this posting is advertised at, based on the lowest and highest locality
rates.

💰💰💰
If this position is not remote and has geographic restrictions, you can instead
specify the salary min and max. For example, if the position is advertised at
GS-15 and the position location is only Washington, DC, then (using 2023 pay
rates):

Minimums:
  GS-15 Step 1: $172,075
Maximums:
  GS-15 Step 10: $183,500

So you would update the line below to look like this:

    {% include job/salary_range.html min="$172,075" max="$183,500" %}

To use the autoomatic salary ranges, leave the lines as-is.

🔻🔻🔻🔻🔻
{% endcomment --------------------------------------------------------------- %}
{% include job/salary_range.html min="" max="" %}

Your salary, including base and locality, will be determined upon selection,
dependent on your actual duty location. Please note the maximum salary available
for the GS pay system is $183,500. For specific details on locality pay, please
visit [OPM's Salaries & Wages page](https://www.opm.gov/policy-data-oversight/pay-leave/salaries-wages/)
or for a salary calculator
[OPM's 2023 General Schedule (GS) Salary Calculator](https://www.opm.gov/policy-data-oversight/pay-leave/salaries-wages/2023/general-schedule-gs-salary-calculator/). You can find more
information in our
[compensation and benefits section]({% link pages/compensation-and-benefits.md %}).

{% comment %}🔻🔻🔻🔻🔻{% endcomment %}
**Travel requirement:** Occasional travel may be required up to 10%-20% per year.

{% comment %}🔻🔻🔻🔻🔻{% endcomment %}
**Work schedule:** Full time.

{% comment ------------------------------------------------------------------ %}
Pick one of the two paragraphs below, depending on whether the position is
perm or term. Delete the one you don't need.
🔻🔻🔻🔻🔻
{% endcomment --------------------------------------------------------------- %}
**Appointment type:**
Permanent hire. This is not a term limited opportunity. Applicants who are
selected for this opportunity will have career conditional status in the federal
government for their first three years of employment and transition to career
after three years. This means you will be a permanent federal employee with no
expiration date.

Learn more about the benefits of working at [GSA](https://www.gsa.gov/portal/category/26702)
and [TTS]({% link pages/compensation-and-benefits.md %}).

## Role summary

{% comment %}🔻🔻🔻🔻🔻{% endcomment %}
The People Operations team at TTS are experts in people related policy,
regulations and administrative requirements. They create and maintain the
infrastructure and support that’s needed to meet the requirements of hiring and
working within the federal government. Moreover, they seek to create an
environment where our people can focus on the work that matters and make sure
TTS employees have everything they need to do great work.

As the People Operations Director, you will oversee areas of Business Operations
including performance management, events and training management, travel,
personnel action requests, leave and time management, purchasing, career
progression frameworks and supervisor training and development. You will work
with experts in these areas and ensure that they have the support that they need
to deliver. You will help unblock roadblocks, interpret policy and lead
strategically. Success in this role will require strong collaboration,
experience navigating complex problems and systems and an ability to lead with
trust.

## Key objectives

{% comment ------------------------------------------------------------------ %}
Key objectives are automatically converted from the information provided at the
top of the page. The automatic conversion helps ensure that all of our postings
are consistent. If you do not want to use the automatic template, delete the
line below that says {% include job/key_objectives.html %} and add your custom
content in its place.
{% endcomment --------------------------------------------------------------- %}

{% include job/key_objectives.html %}

## Qualifications

Provide as much detail as possible on your resume so that we can evaluate your
previous experience. Follow our
[guidance on creating a federal style resume.](https://join.tts.gsa.gov/resume/)

Failure to provide required information may result in disqualification.

For each job on your resume, provide:

- The exact dates you held each job (from month/year to month/year or “present”)
- Number of hours per week you worked (if part time)

**SPECIALIZED EXPERIENCE REQUIREMENTS:**

To qualify, you must have one (1) year of specialized experience at the next
lower GS-grade (or equivalent). Specialized experience is defined as follows:

- Experience leading the development, delivery or integration of highly complex
  digital products or services.
- Experience applying leading industry practices in the design, development and
  delivery of digital products or services. This experience may include
  experimentation based frameworks, iterative development methodologies,
  user-centered design, planning tools or continuous delivery methodologies.
- Experience crafting or creating product vision, strategy or road maps.
- Experience working with cross-functional teams.

## How to Apply

{% include job/apply_button.html %}