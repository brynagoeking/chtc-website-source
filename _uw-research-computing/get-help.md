---
highlighter: none
layout: markdown-page
title: Get Help
---

### There are multiple ways to get help from CHTC staff. See below:

## Research Computing Facilitators

<div class="row justify-content-around d-none d-sm-flex">
    {% assign facilitators = site.data.team | where: "is_facilitator", "1" %}
    {% for facilitator in facilitators %}
        <div class="col-auto">
            <figure class="p-3 d-flex flex-column">
                <img style="object-fit: cover; border-radius: 50%; width: 12rem; height: 12rem" class="mx-auto" src="{{ facilitator.image | relative_url}}" alt="{{ facilitator.name}}'s Headshot">
                <figcaption class="mt-1 text-center"><b>{{ facilitator.name }}</b><br>{{facilitator.title}}</figcaption>
            </figure>
        </div>
    {% endfor %}
</div>


To help researchers effectively utilize computing resources, our Research
Computing Facilitators (RCFs) not only assist your in
implementing your computational work on CHTC compute resources
resources, but can also point you to other on- and off-campus services
related to research computing and data needs. For example, RCFs can: 

* Assist with planning your computational approach for a research
problem 
* Teach you to submit jobs to CHTC compute systems 
* Help you with troubleshooting on CHTC compute systems 
* Connect you with other researchers using similar software or methods 
* Point to learning materials for programming and software development 
* Help you identify applicable non-CHTC data storage options provided by DoIT 
* Find the person who knows the answer to your question, even if the RCF doesn't 
* ... and other helpful activities to facilitate your use of cyberinfrastructure

## Get An Account

If you don't have an account yet, please fill out our [Request
Form](form.html), and we'll follow up quickly to set up a meeting time
and create accounts. If you don't have an account but just have general
questions, feel free to send an email to chtc@cs.wisc.edu (see below).

## Request a Quota Change

If you'd like to request a change in your quotas for one of our data
storage locations, please see our [Request a Quota Change](quota-request) guide.

## Help Via Email

We provide support via email at the address
[chtc@cs.wisc.edu](Mailto:chtc@cs.wisc.edu), and it's never a bad idea
to start by sending questions or issues via email. You can typically
expect a first response within a few business hours.

When emailing us for assistance in troubleshooting an issue, please provide which system you are using, 
an explanation of what you expected to happen versus what actually happened, and  
include relevant files (or provide the locations of them on the system), such as:

* The job submit file (.sub)
* The job executable (.sh) or list of commands used in an interactive job
* Standard error and standard output files (usually .out or .err)
* If on the HTC system, the HTCondor log file (.log)

We will use this information to give you more effective responses and solutions.

## Office Hours

<!-- **Cancellations will be announced via email and on this webpage.**

**We will have a limited office hour schedule over the winter break, beginning Dec. 18.**
**Office hours will only be held on the following dates during this period:**

- **Thursday, Dec. 21st, 3:00 - 4:30 pm**
- **Thursday, Jan. 4th, 3:00 - 4:30 pm**
- **Thursday, Jan. 11th, 3:00 - 4:30 pm**
- **Thursday, Jan. 18th, 3:00 - 4:30 pm**

**Our regular office hour schedule will resume Jan. 22.** 
-->

For users who already have accounts, we have drop-in office hours, online, during the following times:

-   Tuesday morning: 10:30 am - 12:00 pm. 
-   Thursday afternoon: 3:00 - 4:30 pm.

To drop in, find the videoconference link in either your email or in the 
login message when you log into a CHTC server. 

As always, if the times above don't work for you, please email us 
at our usual support address to schedule a separate meeting. 

[Click to sign-in for office hours](sign-in.html)


<!-- For users who already have accounts, we have drop-in office hours on:

-   **Tuesday/Thursday afternoons, from 3:00 - 4:30 pm.**
-   **Wednesday morning from 9:30 - 11:30 am**

Office Hours are located in the [Discovery
Building](http://map.wisc.edu/s/919bjy8v) at the second-floor round
table, just off of the main staircase.\
 **For researchers without access to the upper floors of the Discovery
Building, check in at the front desk and ask them to "call CHTC."**\
 We will confirm that you are here for office hours and you will be let
upstairs. (Note: If you ask the desk to call for a facilitator, by name,
no one will answer as facilitators will not be in their *own* offices
during Office Hours.) --> 

## Make an Appointment

We are happy to arrange meetings outside of designated Office Hours, per
your preference. Simply email us at the address above, and we will set
up a time to meet!
