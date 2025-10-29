# 🌱 Planto 
## Your Smart Plant Watering Reminder


## 🌟 Overview

Planto is a native iOS application built with SwiftUI designed to help plant lovers manage their indoor gardens effortlessly. It simplifies the often-complex task of plant care by providing a clean interface to track watering needs, light requirements, and room locations for all your plants, complete with local notifications for timely watering reminders.


## ✨ Features

Customizable Plant Profiles: Easily add and edit new plant entries with details like name, room location, light requirements, and specific water amount/schedule.

Intelligent Water Tracking: Mark plants as watered for the day with a simple tap, contributing to a daily progress bar.

Progress Dashboard: A visual progress bar on the main screen shows how many of your plants have been cared for today.

Empty State Management: Clear, engaging screens for when the plant list is empty or when all daily tasks are complete.

Swipe-to-Delete: Quickly delete plant entries using a horizontal swipe action.

Local Notifications: Schedules daily watering reminders for each plant to ensure nothing is missed (notifications fire daily at 9:00 AM).

Persistence: Uses UserDefaults to save all your plant data locally.

## 🛠️ Technology Stack

Language: Swift 5+

Framework: SwiftUI

Data Management: ObservableObject and @StateObject (MVVM-like approach)

Data Persistence: UserDefaults with Codable

Notifications: UserNotifications framework (for local scheduling)
