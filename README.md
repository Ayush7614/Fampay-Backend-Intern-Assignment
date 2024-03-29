# Fampay-Backend-Intern-Assignment
This is the Assignment task for Fampay Backend Intern

# Project Goal
To make an API to fetch latest videos sorted in reverse chronological order of their publishing date-time from YouTube for a given tag/search query in a paginated response.

# Basic Requirements
- Server should call the YouTube API continuously in background (async) with some interval (say 10 seconds) for fetching the latest videos for a predefined search query and should store the data of videos (specifically these fields - Video title, description, publishing datetime, thumbnails URLs and any other fields you require) in a database with proper indexes.
- A GET API which returns the stored video data in a paginated response sorted in descending order of published datetime.
- A basic search API to search the stored videos using their title and description.
- Dockerize the project.
- It should be scalable and optimised.

# Instructions:
- Add support for supplying multiple API keys so that if quota is exhausted on one, it automatically uses the next available key.
- Make a dashboard to view the stored videos with filters and sorting options (optional)
- Optimise search api, so that it's able to search videos containing partial match for the search query in either video title or description.
- You are free to choose any search query, for example: official, cricket, football etc. (choose something that has high frequency of video uploads)