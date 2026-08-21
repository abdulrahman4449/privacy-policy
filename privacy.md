---
meta-viewport: width=device-width, initial-scale=1
title: MEDCOM Dispatch — Privacy Policy
---

# Privacy Policy — MEDCOM Dispatch

Last updated: 21 August 2026

**This app is not a medical device.** It does not diagnose, treat, cure or
prevent any medical condition. It is a workforce tool used by ambulance staff to
coordinate calls and record shift activity. It gives no clinical advice. For medical
advice, diagnosis or treatment, consult a qualified healthcare professional.

MEDCOM Dispatch is an internal operational tool for an ambulance service. It is used by
that service's own dispatch staff, crews and administrators, on accounts issued to them
by their employer. It is not a consumer app and is not intended for use by patients or
members of the public.

## Who is responsible for your data

The ambulance service that operates this board is the data controller. It decides who
holds an account, what is recorded, and how long it is kept. Questions about your own
data should go to that service's administrator in the first instance.

## What the app records

| Category | What it holds |
| -------- | ------------- |
| Staff account | Employee ID, display name, role (crew, dispatcher, administrator), and a hash of the account password. Passwords are not stored in readable form. |
| Shift activity | Which vehicle and seat a person signed into, sign-on and sign-off times, overtime, vehicle checklists filed, and messages or issues raised during the shift. |
| Operational records | Details of each call: the nature of the call, pickup point and destination, timestamps for each stage, the crew who ran it, the outcome, and — where the service records it — a patient medical record number (MRN). |
| Vehicle location *(only on an active call, and only if you agree)* | Where your vehicle is while it is running a call: latitude and longitude, how accurate the fix is, heading and speed where the device reports them, the time of the fix, the vehicle and call it belongs to, and the name and employee ID of the crew member whose device sent it. Only the most recent position for a vehicle is held, and it is deleted when the call ends. See "Location while on a call" below. |
| Your answer about location | Whether you agreed to share your vehicle's position or declined, the date and time of that answer, the reason you gave if you declined, and whether an administrator has acknowledged it. The answer is also noted in the shift activity log. |
| On your device | Your sign-in session, sound and theme preferences, and any records waiting to be sent while the device is offline. These stay in the browser's local storage on that device. |

**Patient information.** Where the service records an MRN against a call, that
is health-related information about a third party. It is entered by staff in the course of
their duties, is visible only to signed-in staff of that service, and is governed by the
service's own clinical records and confidentiality rules.

## Location while on a call

So that the desk can send the nearest available vehicle, the app can share a vehicle's
position with the dispatch desk while that vehicle is running a call. This is off until
you agree to it, and it works under fixed limits:

- **Only if you agree.** Before any position is collected, the app explains in plain
  language what is shared, when, who sees it, and what happens if you say no. That is
  separate from the permission dialog your phone or tablet shows. Nothing is collected
  until you have said yes to both.
- **Only during an active call.** It starts when your vehicle is dispatched and stops the
  moment you go back in service. Between calls, on standby, and off shift, nothing is
  collected.
- **Never in the background.** It runs only while the app is open on the screen. Locking
  the device or switching to another app stops it. There is no background location
  collection and no persistent notification keeping it alive.
- **One device per vehicle.** Only the device signed into the seat responsible for the
  call sends a position. A second crew member's device on the same vehicle sends nothing.
- **No route and no history.** A position is saved about once a minute and each one
  replaces the one before it, so only the vehicle's latest position exists. No trail,
  route or history of where you have been is built or stored.
- **Deleted when the call ends.** Going back in service removes the position. As a
  backstop, any open board also removes a stored position when the vehicle is no longer on
  a call or the position has not been updated for 15 minutes — so nothing is left behind
  by a device whose battery went flat or that was closed mid-call.
- **Who can see it.** Dispatch staff and administrators of your own service, on that
  service's own server, alongside the rest of the board. It is not sent to any other
  company, is not used for advertising or analytics, and is not used to monitor staff
  outside the call it belongs to.

**If you say no.** Everything else in the app works exactly as it does now — you take
calls, stamp times, file checklists, all of it. The desk simply sees no position for your
vehicle. A refusal takes effect immediately and needs nobody's approval; an administrator
can record that they have read it, but cannot overturn it. The service asks you to give a
reason, which is kept for administration, and you will be asked again on your next call.

**Changing your mind after agreeing.** Turning location off for this app in your device
settings stops any position being sent, straight away — the app is told the device refused
and says so on your screen. Tell your administrator as well, so the record of your answer
matches what you have decided.

## What the app does not do

- No advertising, and no advertising identifiers.
- No analytics or tracking software, and no third-party trackers of any kind.
- No sale or sharing of any data with third parties.
- No location tracking outside an active call, and none at all unless you have agreed to
  it — see "Location while on a call". No background location, no tracking between calls
  or off shift, and no history of where a vehicle has been.
- No access to contacts, photos, microphone or camera.

## Where it is stored

All records are held on the server operated by the ambulance service itself, in a single
database file. Nothing is sent to any other company's service. Traffic between the app
and that server travels over HTTPS.

## Notifications

If you allow notifications, the app raises an alert on your device when a call is
assigned to your vehicle. Notifications are generated by the app on your own device.
Turning them off in your device settings does not affect anything else.

## How long it is kept

Operational records are retained by the ambulance service under its own records-retention
rules, which typically require ambulance and patient records to be kept for a defined
period. Staff accounts are kept while the person is employed in a role that needs one.
Vehicle positions are the exception: they are not retained at all beyond the call they
belong to, and are removed within 15 minutes at the latest.

## Your rights and how to exercise them

You may ask to see what the app holds about you, to have inaccurate details corrected,
or to have your account removed. See the [account and data deletion page](https://medcom-server.onrender.com/data-deletion) for how to request deletion
and what can and cannot be removed.

## Changes to this policy

If this policy changes, the date at the top of this page changes with it, and the current
version is always the one published here.

## Contact

**[ORGANISATION NAME]**  
**[CONTACT EMAIL ADDRESS]**  
**[POSTAL ADDRESS]**

**Note for whoever publishes this app:** the three bracketed fields above
must be filled in before submitting to Google Play — a privacy policy without a working
contact route is rejected. This document describes what the software actually does and
is written to be accurate, but it has not been reviewed by a lawyer. Have your
organisation's legal or compliance team check it against the health-data law that
applies to you before you publish.
