# Overwatch Champions Series (OWCS)

## Project Overview
OWCS is a dynamic web application that provides information about professional Overwatch esports teams and players across different regions. The platform offers statistics, team rosters, and player profiles.

## Features
- Regional team filtering (NA, EU, China, Asia)
- Detailed player profiles with statistics and most-played heroes
- Real-time search functionality for teams and players
- Multi-language support (English, Spanish, Korean, Chinese)
- Dark/Light theme toggle
- Interactive statistics visualization
- Responsive design for all device sizes

## Browser Compatibility
- Chrome
- Firefox 
- Safari 
- Edge 
- Mobile browsers

## Developer Manual Link
For detailed technical documentation, please refer to the [Developer Manual](#developer-manual) below.

---

# Developer Manual

## Deployment to Vercel
https://project-final-submission.vercel.app/ 


## API Endpoints
### Flags
- GET https://flagsapi.com/${player.country}/flat/64.png - Get flags on search
- GEThttps://flagsapi.com/${player.country}/flat/64.png - Get flags on profile
### Statistics
- GET /api/stats/heroes - Get hero pick rates - Get hero pick rates
### Heros
- GET https://overfast-api.tekrop.fr/heroes - Get hero profiles on player cards
### Known Issues and Future Development
1. Hero portrait API occasionally experiences timeout issues
2. Search function may lag with large datasets
3. Language switching doesn't persist after page reload in some browsers
### Future Development Roadmap
- First part:
1.Implement real-time match statistics
2.Add player comparison feature

- Second part:
1.Introduce extra player information
2.Add VOD integration
3.Implement live match notifications

