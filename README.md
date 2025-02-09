# Objects-Registration
ObjectsRegistration is a highly optimized Minecraft plugin designed to track, register, and manage placed blocks, spawned entities, dropped items, and more—ensuring seamless gameplay without rollback issues or disappearing objects. It is built for high-performance servers, preventing lag while maintaining full registration consistency.


🔹 Features

✅ Item & Block Registration – Prevents placed blocks and items from disappearing due to lag.

✅ Entity Tracking System – Ensures all spawned mobs and entities (End Crystals, Item Frames, etc.) are properly registered.

✅ Drop Registration – Prevents dropped items from being lost or disappearing unexpectedly.

✅ Chunk Load Management – Tracks loaded chunks to prevent ghost entities and block rollback.

✅ Auto Log System – Saves activity logs with timestamped entries and automatic log rotation.

✅ Performance Optimization – Implements batch processing, async handling, and debug mode for smoother operation.

✅ Scheduled Maintenance – Periodic cleanup of ghost blocks, untracked entities, and memory management.

✅ Customizable via config.yml – Fully configurable settings, allowing fine-tuned performance adjustments.

✅ Developer-Friendly API – Provides easy-to-use event hooks for other plugins to integrate item and entity tracking.


🔹 How It Works

1️⃣ Blocks & Items – Every placed block and item is tracked, preventing desynchronization due to server lag.

2️⃣ Entities – Ensures all spawned entities are properly registered and do not disappear unexpectedly.

3️⃣ Dropped Items – Tracks all dropped items, preventing them from vanishing in high-latency conditions.

4️⃣ Logging System – Saves every important action in a rotating log file (logs/plugin.log) with timestamps.

5️⃣ Optimized Performance – Uses asynchronous processing and batch updates to avoid performance spikes.

6️⃣ Maintenance Tasks – Periodically removes ghost blocks and unregistered entities, ensuring server integrity.


🔹 Configuration (config.yml)

🔧 Enable or disable individual tracking systems (blocks, items, entities, drops, etc.).

🔧 Control update intervals and batch sizes for high-performance tuning.

🔧 Enable debugging logs for advanced issue tracking.

🔧 Auto-cleanup features to remove untracked entities and optimize memory usage.


🔹 Commands & Permissions

Command	Description	Permission

/itemregistration reload: Reloads the plugin configuration (permission: itemregistration.admin)


🔹 Who Should Use This Plugin?

Survival & PvP Servers – Prevents players from losing items due to lag or chunk unloading.

Large Multiplayer Servers – Handles high player traffic without causing tick lag.

Technical Minecraft Servers – Ensures redstone-heavy worlds remain stable.

Developers – Provides easy integration points for tracking item placements and entity 
management.


🔹 Dependencies

Spigot/Paper 1.20+

Compatible with other plugins that modify item behavior (e.g., custom economy, anti-cheat, etc.)


🔹 Final Note

📌 ObjectsRegistration is designed for efficiency and reliability, ensuring no registered entity or item disappears.

📌 Optimized for minimal performance impact while handling thousands of objects simultaneously.

📌 Fully configurable, extensible, and developer-friendly for easy integration into any server setup.
