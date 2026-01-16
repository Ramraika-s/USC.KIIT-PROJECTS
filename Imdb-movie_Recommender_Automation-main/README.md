# IMDb Movie Recommendation Bot — UiPath Automation

An intelligent UiPath automation workflow that helps movie enthusiasts make informed viewing decisions by fetching live IMDb ratings and providing clear recommendations.

---

## Overview

This automation allows users to input a movie title, performs a web search on IMDb, extracts the movie’s rating, and offers an easy-to-understand watch suggestion based on predefined rating thresholds.

---

## Features

- **User Input:** Prompt for movie name via an interactive input dialog.  
- **Web Scraping:** Automated browser interaction to search IMDb and retrieve ratings in real-time.  
- **Rating-based Recommendation:**  
  - ⭐️ Rating < 5.0 → ❌ Avoid Watching  
  - ⭐️ Rating 5.0–8.0 → ⚠️ Average Watching  
  - ⭐️ Rating > 8.0 → ✅ Must Watch  
- **User-friendly Alerts:** Displays tailored messages based on the movie rating to guide viewing choices.

---

## Technologies Used

- UiPath Studio for robotic process automation and workflow orchestration  
- UiPath Web Automation activities for browser control and data scraping  
- Interactive dialogs for seamless user input and output

---

## Getting Started

1. Clone or download this repository.  
2. Open the project in UiPath Studio.  
3. Run the workflow and enter a movie title when prompted.  
4. Review the recommendation displayed based on the IMDb rating.

---

## Use Cases

- Casual viewers seeking quick, data-driven movie suggestions  
- Movie recommendation automation for personal or social use  
- Base framework for integrating movie rating insights into larger entertainment workflows

---

## Future Enhancements

- Extend recommendations to include genre, synopsis, or cast information  
- Integrate with streaming service APIs to check movie availability  
- Export recommendations and ratings to Excel or other formats for tracking

---

## License

This project is licensed under the MIT License — feel free to use and adapt as needed.

---

## Contact

For questions or collaboration, reach out via [shivamramraika.dev@gmail.com] or open an issue here on GitHub.
