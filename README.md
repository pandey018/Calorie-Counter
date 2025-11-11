Overview
Calorie Counter is a barcode‑enabled mobile nutrition tracker built with Kotlin and Jetpack Compose. It stores data locally with Room (SQL) and is optimized for quick entry, reliable offline usage, and smooth UI.
The app is designed to scale efficiently (tested up to ~1,000 daily active users in local scenarios) and maintain a low crash rate.

Key Features

Quick add & search: Add foods via search or scan packaged items by barcode.
Barcode nutrition lookup: Used Barcode Scanner to add nutrition jus by scanning barcode.
Meals & diary: Track breakfast/lunch/dinner/snacks with macros & calories.
Goals & summaries: Daily targets, progress rings, weekly trends.
Fast & resilient: Compose UI, and memoized calculations keep lists snappy.
Scalable local data: Efficient SQL schema handles 500+ food items per user smoothly.
