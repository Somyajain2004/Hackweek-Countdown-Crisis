fix: handle null data in CommunityInfo and add loading fallback

- Added a null check to prevent crash when data is not yet loaded
- Introduced a loading state while fetching /cosc.json
- Improved error handling for fetch failures
- Ensured safe rendering of community details after successful fetch

