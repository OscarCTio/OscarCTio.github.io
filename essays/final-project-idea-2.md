---
layout: essay
type: essay
title: "Manoa Lost & Found"
date: 2026-03-30
published: false
labels:
  - Software Engineering
  - Nextjs
---

By Oscar Tio, Sebastian Wheelehan, Nathan Wong

## Overview

**Problem:**  
Students frequently lose personal items on campus such as water bottles, keys, ID cards, and electronics. While there are existing lost and found services, they are often centralized, slow, or difficult to access. Many students resort to informal methods such as group chats or social media posts, which are unstructured and easy to miss.

**Solution:**  
Manoa Lost & Found is a web-based platform designed specifically for University of Hawaiʻi at Mānoa students to report, search, and recover lost items. The system allows users to post lost or found items, browse listings by location or category, and connect directly with others to return items efficiently.

## Approach

To use Manoa Lost & Found, users first create an account and log in.

1. **Report a lost item**  
   Users can create a post describing the lost item, including:
   - Item name and description
   - Last known location
   - Date and time lost
   - Optional image

2. **Report a found item**  
   Users who find items can:
   - Post details about the item
   - Include where it was found
   - Upload a photo for identification

3. **Browse listings**  
   Users can:
   - Search for items by keywords
   - Filter by category (e.g., electronics, accessories, IDs)
   - Filter by location (e.g., campus buildings)

4. **Connect and recover items**  
   - Users can contact each other through the platform
   - The original owner can verify and claim the item
   - Items can be marked as “returned” once resolved

## Mockup Page Ideas

- **Landing Page**
  - Recent lost and found posts
  - Quick search bar
  - Categories (Electronics, Clothing, IDs, etc.)

- **Lost Items Page**
  - List of all reported lost items
  - Filters for location, date, and category

- **Found Items Page**
  - List of items that have been found
  - Images and descriptions for easy identification

- **Item Detail Page**
  - Full description of the item
  - Image (if provided)
  - Contact or message option
  - Status (lost, found, returned)

- **Create Post Page**
  - Form for submitting lost or found items

- **User Profile Page**
  - User’s submitted posts
  - Status of items (active, resolved)

## Use Case Ideas

- A student loses their water bottle in the library and submits a “lost item” post.
- Another student finds a water bottle in the same location and submits a “found item” post.
- The original owner searches the platform and finds a matching description.
- They contact the finder and verify ownership.
- The item is returned and marked as resolved.

## Beyond the Basics

- **Image Matching (optional)**
  - Suggest possible matches between lost and found items using image similarity

- **Location-Based Filtering**
  - Map-based interface showing where items were lost or found

- **Notification System**
  - Notify users when a matching item is posted

- **Verification System**
  - Require users to describe unique features to claim an item

- **Reputation System**
  - Reward users for returning items

- **Mobile-Friendly Design**
  - Optimized UI for quick posting and searching on phones
