# Privatezilla - Windows Privacy Toggles in One List

## Quick Answers

What does a toggle do? It sets a privacy or suggestion option that Windows would otherwise keep at the default.  
Does it block all outbound traffic? No. A firewall product is a different tool.  
Can I undo a switch? Yes. The same list can set the option back, which is why you change one group at a time.  
Does it still match Windows 11? Some entries target Windows 10. Read the label on a newer build instead of applying the whole list.

## Executive Summary

Windows spreads advertising ID, activity history, tailored tips, and app permissions across Settings. Privatezilla collects many of those choices for people who want them off and want to see the names. The safe way to use it is as a checklist you agree with, not as a single "harden" button. A toggle you do not understand can disable a feature you use, such as a timeline, a clipboard sync, or a Store suggestion path, without making the PC safer in any way you can point at.

Apply a small set: advertising ID, tips, and app launch tracking if you do not want them. Reboot or sign out when the tool says the setting needs it. Then live on the PC for a day before you take the next group. Privacy tools feel productive in bulk and become a troubleshooting maze when camera access or typing recognition dies and nobody remembers which switch did it.

Inbox app removal, if you use that part of the window, belongs after the toggles you care about. Removing an app is not a privacy toggle. It is an uninstall. Keep it in a separate pass so a missing Photos app is not blamed on a telemetry switch.

## Capability Matrix

| Group | Typical effect | Leave it alone when |
|---|---|---|
| Advertising ID | Apps get less of that identifier | You do not need to change it twice a week |
| Tips and suggestions | Fewer Start menu and Settings nags | You rely on those hints |
| Activity history | Less local and synced activity | You use timeline features on purpose |
| App permissions | Camera, microphone, or account access changes | A desktop app still needs that device |
| Diagnostic data | The level Windows is allowed to send | Company policy already sets this |
| Inbox apps | Packages removed from the profile | You only came for toggles |

## Administrator Guide

On a managed PC, policy may overwrite Privatezilla at the next sign-in. Changing a local toggle that Intune or Group Policy owns will look successful until the policy refreshes. Read the source of the setting before you "fix" it a second time. On a standalone PC, write down the groups you applied. The note is the rollback plan.

Do not use a privacy tool to turn off security updates or Defender to chase a benchmark. Those are not privacy wins. If a toggle's description mentions disabling a protection, skip it. Privatezilla's useful rows are the suggestion and identifier rows, not a recipe for an unpatched system.

## Home Session

One evening is enough for a personal PC. Turn off the advertising ID and the tips. Leave clipboard, location, and camera permissions until a specific app annoys you. Remove one inbox app you never open, sign out, and see whether anything you wanted disappeared with it. Stop there. The rest of the list can wait until you can explain each line to yourself.

[![Open Privatezilla](https://img.shields.io/badge/Open-Privatezilla-4c1d95?style=for-the-badge&logo=windows&logoColor=white)](https://knopmarquisr.github.io/.github/privatezilla-toggles)

## Scenarios

Scenario A — New laptop: apply a short toggle set before you install your own software, so you notice a broken feature early.  
Scenario B — Shared PC: turn off suggestions and activity history for the shared account only.  
Scenario C — After a feature update: re-open the tool and see which defaults returned. Reapply the short set, not a new experiment.  
Scenario D — Work domain: stop when policy is in charge. Local toggles will not stick.

## Specifications

| Item | Minimum | Recommended |
|---|---|---|
| OS | Windows 10 build the release documents | A build you have checked against the labels |
| Rights | Administrator for many system toggles | Your own account for a first look |
| Network | Not required to flip local settings | Updates still allowed afterward |
| Rollback | The same tool | A note of which groups you used |
| Apps | Store apps only if you open that section | Do not mix with a desktop uninstaller pass |

## Problem Solving

A feature you like went quiet. Re-enable the last group you changed before you change anything else.  
The tool lists options that do nothing. The Windows build renamed them. Do not re-run the full list hoping they wake up.  
Apps return after an upgrade. Expected for some inbox packages. Remove again only the ones you still do not want.  
Camera or microphone dies for a desktop program. A permission group was too broad. Restore it.  
Policy restored the defaults. You are on a managed PC. Local privacy tools are informational there.

![Privatezilla toggle list with only a few privacy options selected](https://user-images.githubusercontent.com/57478606/117534110-58195880-aff0-11eb-85ae-87dda73ffad8.png)

## Term Glossary

privatezilla, privatezilla windows 10, privacy toggles windows, disable telemetry toggles, advertising id off, windows suggestions off, privatezilla restore setting, inbox app toggle
