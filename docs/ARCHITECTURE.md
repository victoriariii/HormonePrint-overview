# Architecture (high-level)

## Client
Flutter mobile app (iOS/Android)

## Data layer
- User profile: cycle baseline, preferences
- Period history: start/end entries + derived features (cycle length, phase estimate)
- Symptoms & notes (structured + optional free-text)

## Intelligence layer (iterative)
v1: deterministic rules + personalization  
v2: learned personalization based on user patterns  
Principle: recommendations must be explainable and user-controllable.

## Privacy
- Data minimization by default
- Granular consent for any external data (wearables/health)
- Export/delete controls

