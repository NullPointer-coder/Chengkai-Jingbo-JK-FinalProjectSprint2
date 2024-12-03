# Chengkai-Jingbo-JK-FinalProject-Sprint 2

## Team Name:

JK

## Team member name:

Jingbo Wang, Chengkai Yang 

## Technical Update

### 1. Tech Stack 

Frontend: Initial UI layout using [Framework/Library, e.g., Flutter/React Native].

Backend: Firebase (Authentication, Analytics, Database).
Language: [Programming language used, e.g., Kotlin].

### 2. APIs

Spoonacular API: Fetches recipe recommendations based on inputted ingredients and preferences. (Implementation in progress)

Google ML Kit: Scans barcodes for ingredient code numbers.

Open Food Facts API： Get ingredient details form code numbers. (Implementation in progress)

### 3. On-Device Sensors

Camera: Barcode scanning for ingredients.

### 4. Database Schema (Implementation in progress)

Users Table: Manages user details for personalization.
Ingredients Table: Stores ingredient details entered by users.
Recipes Table: Saves fetched or user-created recipes.
Recipe Ingredients Table: Links recipes and ingredients in a many-to-many relationship.
Offline Cache Table: Caches recipes and interactions for offline functionality.
Analytics Table: Tracks user activity using Firebase Analytics.

Database Relationship Diagram
Users → 1-to-many → Ingredients
Users → 1-to-many → Recipes
Recipes → many-to-many → Ingredients (via Recipe Ingredients)
Users → 1-to-many → Offline Cache
Users → 1-to-many → Analytics

## Demo

### Completed Features

User Registration/Login: Functional Firebase Authentication.

Barcode Scanning: Utilized Google ML Kit for ingredient input.

Preliminary UI:

Ingredient Input Screen

Recommendation Page (UI only, backend integration pending).

Recipe Details Screen (basic layout).

### Missing Features

Database connectivity for ingredients and recipes.

Integration of Spoonacular API for live recommendations.

## Chengkai-Jingbo-JK-FinalProject: Fridgify

(Smart Recipe Recommender)[https://github.com/NullPointer-coder/Chengkai-Jingbo-JK-FinalProject.git]

