---
description: >-
  The “Company Setting” tab allows the user to edit select fields related to a
  company profile.
icon: wrench
---

# Company Settings

This section allows administrators to configure core account options, including company details, time zone, pay period settings, employee information, and other default preferences. It’s the main area for setting up and managing how your time clock system operates.

## Basic Setting

***

1. **Company ID-** A unique system-generated identifier for your company account. This cannot be changed and is used for support and record purposes.
2. **Company Name-** The official name of your company as it will appear across the system (reports, timesheets, etc.).
3. **Name Display Format-** Controls how employee names appear throughout the platform (e.g., Last Name, First Name, or First Name Last Name).
4. **Timezone-** Sets the time zone for your company to ensure accurate timekeeping, reports, and employee clock-ins/outs.
5. **Company Logo Upload-** Allows you to upload or remove your company’s logo (optional, max height 40 pixels). The logo can appear on reports and company dashboards.

***

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

## Breaks & Lunches

**Breaks & Lunches in TimeClockFree** let administrators define company rules for employee breaks and lunch periods. This section allows you to set automatic or manual break deductions, specify paid or unpaid breaks, and customize break durations to match company policies and labor regulations. By configuring these settings, the system can accurately track employee work hours while handling break compliance automatically.

***

#### **Break Button Section**

* **Report Label (Break):** Lets you set the name/label that appears on reports for employee breaks.
* **Pay (Unpaid):** Determines whether the break time is paid or unpaid.

***

#### **Lunch Button Section**

* **Report Label (Lunch):** Lets you set the name/label that appears on reports for employee lunches.
* **Pay (Paid):** Determines whether the lunch period is paid or unpaid.

***

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

## Payroll Settings

It allows administrators to configure how employee work hours are calculated for payroll. This includes setting pay periods, overtime rules, rounding policies, and other options that ensure accurate wage calculations. By customizing these settings, the system can automatically prepare time data in a format that matches your payroll process.

***

#### **Payroll Frequency**

* **Frequency (Monthly, Biweekly, etc.):** Sets how often payroll cycles occur.
* **1st Period Start:** Select the start day of your payroll cycle.

***

#### **Electronic Timecard Approval**

Let's you enable approval requirements for different employee types:

* **Hourly Worker Timecard Approval:** Requires approval of timecards for hourly workers.
* **Salaried Worker Leave Approval:** Requires approval for leave entries of salaried staff.
* **Manager Timecard Approval:** Allows managers to review and approve employee timecards.

***

#### **Current Payroll Period**

* **Start Date / End Date:** Shows the current payroll period dates.
* **Reopen Prior Period:** Lets you reopen and adjust the previous payroll period if needed.

***

#### **Payroll Export**

* **Export Option (e.g., Paychex Flex Payroll):** Choose the payroll system to export employee time data.
* **Setup Button:** Configure integration and export settings to match your chosen payroll provider.

***

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

## Time Settings

It allows administrators to control how time is tracked, displayed, and calculated for employees. This includes setting workweek start days, time formats, rounding rules, overtime settings, and other options that affect how hours are recorded and reported. By customizing these settings, companies can ensure accurate timekeeping that matches their internal policies and labor requirements.

***

#### **Workweek Starts On**

Select the day your company’s workweek begins (e.g., Monday, Sunday). This affects weekly overtime calculations and reporting.

***

#### **Average Hours per Week for Salaried Workers**

Enter the default weekly hours for salaried employees. Used to calculate overtime and accruals correctly.

***

#### **Include Paid Leave in Weekly Overtime Calculations**

When checked, paid leave hours (vacation, sick time, etc.) are included when calculating weekly overtime totals.

***

#### **Include Hours Worked Past Midnight with Prior Day**

When checked, hours worked past midnight are grouped with the previous day’s totals instead of starting a new day at midnight.

***

#### **Hours Clocked Out Before Restarting Daily Totals**

Set the number of off-clock hours required before a new daily total begins (helps separate shifts for overnight workers).

***

#### **Round the Time During Calculation**

Choose how time is rounded (e.g., to the nearest tenth hour, quarter hour). This standardizes how worked hours are calculated.

***

#### **Display Total Time As**

Select how worked hours are displayed in reports — either in hour:minute format or decimal format.

***

#### **Date Format**

Choose how dates appear throughout the system (e.g., Canada format YYYY-MM-DD or US format MM/DD/YYYY).

***

#### **Time Format**

Choose 12-hour or 24-hour clock format for how time entries appear (e.g., 2:30 PM or 14:30).

***

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

## Security

It lets administrators manage account safety and access controls. This section includes settings for password requirements, login restrictions, IP filtering, and session controls. By configuring these options, companies can ensure that only authorized users access their timeclock system and that sensitive employee time data is protected.

***

#### **Administrators List**

Shows the list of administrator accounts with access to company settings.

* **Edit Button:** Lets you add, remove, or adjust administrator permissions.

***

#### **Password Rules**

Controls how passwords work for your users:

* **User Can Modify Their Password:** Allows employees or managers to change their own passwords.
* **Minimum Password Length:** Lets you set the minimum number of characters required for passwords to improve security.

***

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

