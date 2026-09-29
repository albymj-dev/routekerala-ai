# RouteKerala AI 🚚❄️

A smart cold-chain monitor and emergency rerouting dashboard built for the KeralAI Grand Challenge 2026.

## What is this?
A lot of fresh seafood moves daily from harbors around Alappuzha and southern Kerala up toward Cochin Port (ICTT Vallarpadam). Because routes like NH 66 frequently face traffic bottlenecks, construction, or bad weather, refrigerated trucks can easily get stuck. 

If a truck's cooling system starts acting up during a delay, drivers and dispatchers usually don't realize the catch is spoiling until the truck reaches the port gate—where the entire consignment ends up rejected. 

We built **RouteKerala AI** to solve that blind spot.

## What it does
* **Monitors Container Health:** Keeps tabs on inside cargo temperature, ambient conditions, and traffic delays along the route.
* **Predicts Spoilage in Real Time:** Compares estimated arrival time against how long the cargo can safely last before spoiling.
* **Auto-Reroutes to Emergency Hubs:** If the system detects that the shipment won't make it to Cochin Port in time, it automatically finds and routes the truck to the nearest certified cold storage facility (like the seafood processing belt in Aroor) so the cargo can be saved.

## Tech We Plan to Use
* **Interface & Map:** JavaScript, Leaflet.js, and Tailwind CSS for the live fleet dashboard.
* **Data & Logic:** Python with Pandas to handle route waypoints and simulated temperature telemetry.
* **AI & Alerts:** IBM watsonx / Python machine learning models for anomaly detection and spoilage risk calculation.

## Team ColdSync
* Alby Mathew Joshy
* Abhishek S Nair
* Calvin Sunil
* Haadiya Aboobacker
* Sneha Shaiju

*Mar Baselios Institute of Technology and Science*
