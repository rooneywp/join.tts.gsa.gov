---
title: Login.gov Security Engineer Tech Expert - Analyst 
# permalink: /join/performance-profiles/login.gov-security-engineer-tech-expert-analyst/
# state: upcoming
# job_post_type: usajobs
# parent_position_name: Login.gov Security Engineer Technical Expert GS15
# parent_position_link: /join/login.gov-security-engineer-technical-expert/
# related_performance_profiles:
#  - name: Login.gov Security Engineer Tech Expert - Purple Team
#    link: /join/login.gov-security-engineer-tech-expert-purple-team/
#  - name: Login.gov Security Engineer Tech Expert - Security Operations
#    link: login.gov-security-engineer-tech-expert-secops/
# apply_url: TBD
# contact_name: TTS Talent Team
# contact_email: jointts@gsa.gov
# INSTRUCTIONS UPCOMING: These fields are required for upcoming
# role_name: Security Engineer Tech Expert - Analyst
# gs_level: 15
# org: 'Login.gov'
---
{% if page.state == 'upcoming' %}
{{ page.org }} will soon be accepting applications for GS-{{ page.gs_level }} - {{ page.role_name }} roles. If you'd like to be
  notified when these positions are open, sign up to our [mailing list]({{ site.baseurl }}/newsletter). More details are available on [the main {{ page.parent_position_name }} posting]({{site.baseurl}}{{ page.parent_position_link }}).
{% endif %}

{% if page.state != 'upcoming' %}
{{ page.org }} is hiring for the role of GS-{{ page.gs_level }} {{ page.role_name }}. **There are several {{ page.org }} teams hiring for this role.** This page contains a summary of the {{ page.title }} role. [View descriptions of other {{ page.org }} {{ page.role_name }} positions.]({{site.baseurl}}{{ page.parent_position_link }})
{% endif %}

## Role summary

As a security analyst technical expert, you will report to Login.gov’s security branch chief. In this fully remote position, you will work closely with Login.gov’s product and platform teams to improve Login.gov’s defensive capabilities. You will play a key role in helping Login.gov’s security team implement best practices to protect user data, secure Login.gov’s application and infrastructure, and combat fraud and abuse. You will provide strategic guidance to Login.gov’s leadership team, provide feedback on security program objectives, and lead improvements to Login.gov’s cybersecurity practice.

## Key objectives

### Objective #1: Contribute to Login.gov’s Cybersecurity Practice
- Contribute to vulnerability testing and analysis, incident response and analysis, alert response and analysis activities.
- Conduct data analytics activities to support monitoring, detecting, defending against, or responding to security incidents.
- Automate data analytics or security processes by using object-oriented languages (e.g., Python).
- Collaborate with application development teams, platform engineers, and Security Operations Center (SOC) engineers to build and implement security in an open source, live services environment.
- Collaborate with User Experience, Infrastructure, and Application Developer Engineers to ensure changes to Login.gov’s product or infrastructure do not negatively impact security.


### Objective #2: Provide subject matter expertise on cybersecurity practices to Login.gov Leadership 
- Provide guidance on industry standards (e.g., NIST 800 series) and best practices to product managers and application developers
- Develop standard operating procedures that improve Login.gov’s cybersecurity posture.  
- Collaborate with site reliability engineers to enhance cloud platform security engineering practices.
- Improve Login.gov’s security operations via automation.
- Communicate with internal and external partners to share Login.gov’s security posture, risk, and operational processes. 
- Contribute to security program goal setting and roadmapping activities.


### Objective #3: Ensure Login.gov maintains its FedRAMP authorization
- Maintain systems that comply with NIST-800-53 controls. 
- Develop and maintain artifacts for cybersecurity assessments 
- Participate in technical interviews for cybersecurity assessments
- Prepare application developers, site reliability engineers, or platform engineers for technical assessment interviews
- Propose changes to Login.gov development and site reliability engineering practices to better support automated compliance


##Objective #4: Collaborate effectively on distributed, agile teams
Share knowledge and work collaboratively to integrate anti-identity fraud principles into product and engineering practices. 
Participate in regular retrospectives and provide feedback to help improve the way the team works.
Promote a work environment of respect, diversity, equity, inclusion, accessibility, mutual support, continuous learning, and commitment to customer / partner needs.


## {{ page.related_performance_profiles | size | plus: 1 }} {{ page.org }} teams are hiring for this role

The links below provide descriptions specific to each {{ page.org }} team. When the role is posted and open for application on USAJobs, you can indicate which team(s) you’re interested in.
{% for profile in page.related_performance_profiles %}
  - [{{profile.name}}]{{site.baseurl}}({{profile.link}})
{% endfor %}

## Preparing to apply

This Join TTS site has information about [the application process](https://join.tts.gsa.gov/hiring-process/) and [how to prepare a government-style resume](https://join.tts.gsa.gov/resume/).