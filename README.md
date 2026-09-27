# Runbo — product and engineering case study

**An independent iPhone and Apple Watch product by [Andrei Pervychine](https://andrei.pervychine.com/).**

[Product website](https://runbo.app/) · [App Store](https://apps.apple.com/us/app/runbo-workout-guidance/id6756812213) · [Architecture and trade-offs](ARCHITECTURE.md)

This repository documents the shipped product using public materials. It contains no application source code. My professional work and other products are on my [portfolio](https://andrei.pervychine.com/).

## The problem

A self-coached runner can have plenty of training data and still need help choosing today's session. Runbo brings Apple Health signals into a daily view and connects a suggested session to a structured Apple Watch workout.

## Product surfaces

<table>
<tr><th>iPhone daily view</th><th>Apple Watch workout</th></tr>
<tr>
<td><img src="https://runbo.app/languages/english/01-home.png" width="260" alt="Runbo iPhone dashboard with readiness and training information"></td>
<td><img src="https://runbo.app/watch-todays-workout-v1.png" width="260" alt="Runbo Apple Watch suggested workout"></td>
</tr>
</table>

Screenshots are published product images from [runbo.app](https://runbo.app/); displayed values are illustrative, not adoption or performance measurements.

## Engineering scope

- **Native product:** Swift and HealthKit, with iPhone and Apple Watch experiences.
- **Data interpretation:** workout history, sleep and recovery signals inform readiness and daily guidance. Availability varies with the data shared into Apple Health.
- **Actionable output:** structured sessions can be sent to Apple's Workout app, including intervals and pace or heart-rate targets.
- **Watch experience:** today's guidance and selected metrics remain available without the iPhone nearby.

The [architecture note](ARCHITECTURE.md) separates observable product behavior from design implications. It does not claim unpublished algorithms, benchmarks or backend implementation details.

## Evidence and boundaries

The [App Store listing](https://apps.apple.com/us/app/runbo-workout-guidance/id6756812213) identifies Andrei Pervychine as the developer and provides a release history. The [portfolio](https://andrei.pervychine.com/) identifies Runbo as an independent project. The [product site](https://runbo.app/) documents current features and screenshots.

This demonstrates a released product spanning health-data integration, mobile interfaces and a watch workflow. No user-count, revenue, clinical-accuracy or performance claim is made here. Runbo provides fitness guidance; it is not a medical device.

Public sources reviewed September 27, 2026. Product capabilities may change; consult the live product site and privacy policy for current availability and data handling.
