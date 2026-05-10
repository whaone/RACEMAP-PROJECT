🏁 Racemap: Hybrid Live Tracker
Racemap is a developer-focused prototype designed to solve the "spectator problem" in amateur racing. Usually, tracking requires expensive GPS chips; Racemap allows any rider with a smartphone to join the map instantly.

🚀 The Hybrid Strategy
This project uses a unique two-tier approach to location data:

Option A: Strava Beacon Integration
Riders who already use Strava can simply paste their Beacon Safety Link. The backend acts as a proxy to extract real-time coordinates, allowing riders to keep their existing workout flow without opening another app.

Option B: Direct Web-GPS Tracker
For maximum accuracy and zero lag, riders can use the built-in Direct Tracker. Using the browser's Geolocation API, it streams high-precision coordinates directly to the map via WebSockets/Firebase.
