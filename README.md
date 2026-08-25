TODOCOCCUS - SUPPORT
Last updated: 25 August 2026


WHAT THIS IS

Todococcus turns the household's Apple Reminders into quests. Finishing
a quest feeds a creature, and creatures grow through twelve stages as
the family gets things done. Everyone in the household has their own
creature on their own device, and everyone can see how the others are
doing.

There is nothing to lose. No streaks to break, no penalties, no way to
set a creature back by having a slow week. The only direction is
forward, just faster or slower.


GETTING STARTED

1. Install TestFlight from the App Store, then open the invitation
   link you were sent.

2. Sign in to iCloud on the device if you have not already. Todococcus
   stores everything in your own iCloud account, so this is required.

3. Accept the household invitation. This is what connects your device
   to the family's shared creatures and quests.

4. Grant the Reminders permission when asked. Without it the app has
   no quests to show.

5. Your first creature hatches on its own. Its species is decided at
   hatch and is not something you choose.


HOW QUESTS WORK

Quests come from Apple Reminders. Anything in Reminders can become a
quest; nothing needs to be entered twice.

Tags control who a reminder belongs to and how it groups:

  #Capitalized   assigns the reminder to a household member
  #lowercase     groups reminders into a quest group

Completing the reminder in Reminders completes the quest in Todococcus.
You can complete it from either place - the app and Reminders stay in
step.

[VERIFY: confirm the tag rules above match the current quest_mapper
behaviour before publishing. This is written from the design intent,
not from reading the shipped code.]


HOW CREATURES GROW

Stages 1 through 9 are the same for everyone: a shared path from a soft
Cambrian oddity, through armor, spine, lungs, land, and warm blood.

At stage 10 the path splits. Your creature becomes a reptile, a mammal,
or something winged, depending on the species it was given at hatch.
Stages 11 and 12 are specific to that species alone. There are nine of
them, and part of the point is not knowing which one you have until it
shows itself.

Organelles are the small features that appear on a creature as it
progresses. They are earned and they are permanent. They are not
currency, there is nothing to spend them on, and there is no shop.


WHEN SOMETHING IS WRONG

No quests are showing up

  Check Settings > Privacy & Security > Reminders and confirm
  Todococcus is switched on. If it is, check that the reminders in
  question carry the right tags - an untagged reminder is not assigned
  to anyone.

The creature looks different on two devices

  This is almost always a sync delay rather than a fault. Confirm both
  devices are signed in to iCloud, are on a network, and have accepted
  the household invitation. Give it a minute; CloudKit is not instant.
  If a device has never shown the family's creatures at all, the
  invitation was probably never accepted on that device.

A quest was completed but nothing happened

  Completion is read from Reminders, so the reminder itself has to be
  marked done. A reminder deleted rather than completed does not count.

A child's device will not accept the household invitation

  Screen Time may be intercepting it. As family organizer you can allow
  it under Screen Time on that device. Ask to Buy can also sit in front
  of the prompt.

Something is genuinely broken

  Take a screenshot inside the app and TestFlight will offer to send it
  as feedback. That is the fastest route, because the screenshot
  arrives with the device and build details attached.


NOT BUILT YET

  - Apple Watch
  - Shortcuts and Siri
  - The full activity view for adults. The activity ring in the app
    today is deliberately small, not a placeholder for something
    half-finished.

[VERIFY: keep this list honest against what has actually shipped. A
support document that lists a feature as missing after it lands is
worse than no list at all.]


PRIVACY IN ONE LINE

Everything lives on your device and in your own iCloud account. There
are no servers, no analytics, and no third parties. The developer
cannot see your data. The full policy is a separate document.


CONTACT

41.hauteur.boiler@icloud.com
