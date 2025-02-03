# Frontend Assignment v1.0


## Objective:
Develop a simple Next.js frontend that fetches property listings from a provided Yii 1.1 API and displays them in a responsive, user-friendly layout.

## Requirements:
- Create a Next.js project (using Next.js 13+ with App Router or Pages Router).
- Fetch data from an API endpoint (Simulated Yii 1.1 API with REST).

API Endpoint: https://example.com/api/properties

Expected Response:
```
[
  {
    "id": 1,
    "title": "Luxury Apartment in Dubai Marina",
    "price": "2,500,000 AED",
    "image_url": "https://example.com/images/apartment1.jpg"
  },
  {
    "id": 2,
    "title": "Villa in Palm Jumeirah",
    "price": "10,000,000 AED",
    "image_url": "https://example.com/images/villa1.jpg"
  }
]
```
- Display the properties in a responsive grid layout.
-- Show title, price, and image.
-- Use Tailwind CSS or Bootstrap.
- Add client-side filtering (Search bar to filter by title).
- Use Server-Side Rendering (SSR) or Static Site Generation (SSG) for initial data fetching.
- Bonus (Optional but Preferred):
-- Implement a "View Details" button that navigates to a property details page (/property/[id]).
-- Use Next.js Dynamic Routing.
-- Show title, price, full description, and image on this page.

## Evaluation Criteria:
✅ Code Quality (Clean, readable, well-structured)

✅ Next.js Features Usage (SSR, SSG, or Client-side Fetching)

✅ UI/UX (Responsive design, user-friendly)

✅ API Integration (Handles API errors gracefully)

✅ Performance Optimization (Lazy loading images, avoiding unnecessary re-renders)

### Submission Instructions:
- GitHub repo link with a README.md explaining setup and implementation.
- Live demo (if deployed on Vercel or Netlify).
