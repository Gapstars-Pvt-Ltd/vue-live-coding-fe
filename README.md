# Frontend Vue Assessment

Welcome to the live coding test for the Frontend Vue Developer position. This assignment is designed to evaluate your skills in frontend development.

This technical test aims to assess the following skills:

1. Your ability to fluently utilize the Vue framework.
2. Your ability to structure the codebase by applying best practices.
3. Your ability to work with the provided mockup and build the UI with precision.

## What We’re Looking For

We will evaluate your submission based on the following criteria:

- Code readability and maintainability.
- Adherence to design specifications.
- Responsiveness and performance optimization.
- Error handling and robustness.
- Implementation of scalable solutions for handling data.

## Backend API

- [ ] Use this API endpoint: [API endpoint](https://fs-industry-card.onrender.com/api/companies).

  The API returns an array of company objects with the following structure:

  ```json
  [
  {
    "uuid": "811454a4-5640-497a-86da-077b211a7f97",
    "images": {
      "32x32": "https://storage.googleapis.com/dealroom-images-development/e0/MzI6MzI6Y29tcGFueUBzMy1ldS13ZXN0LTEuYW1hem9uYXdzLmNvbS9kZWFscm9vbS1pbWFnZXMvMjAyNC8wNC8zMC9iOGY3YjhlZjQ3M2E0NDlhZjI1OTQ0NDc1ZTgxZmE3Mw==.png",
      "74x74": "https://storage.googleapis.com/dealroom-images-development/23/NzQ6NzQ6Y29tcGFueUBzMy1ldS13ZXN0LTEuYW1hem9uYXdzLmNvbS9kZWFscm9vbS1pbWFnZXMvMjAyNC8wNC8zMC9iOGY3YjhlZjQ3M2E0NDlhZjI1OTQ0NDc1ZTgxZmE3Mw==.png",
      "100x100": "https://storage.googleapis.com/dealroom-images-development/0b/MTAwOjEwMDpjb21wYW55QHMzLWV1LXdlc3QtMS5hbWF6b25hd3MuY29tL2RlYWxyb29tLWltYWdlcy8yMDI0LzA0LzMwL2I4ZjdiOGVmNDczYTQ0OWFmMjU5NDQ0NzVlODFmYTcz.png"
    },
    "income_streams": [
      {
        "id": 3,
        "name": "subscription"
      }
    ],
    "industries": [
      {
        "id": 100147,
        "name": "enterprise software"
      }
    ],
    "name": "OpenAI",
    "tagline": "An AI research and deployment company working on artificial general intelligence and generative AI",
    "total_jobs_available": 58
  },
  ]


### Frontend Implementation

- [ ] Fetch the companies' data from the API.
- [ ] The card's title should be the industry name.
- [ ] Display the count of companies in that industry at the top right corner of the card.
- [ ] Implement the company grouping logic by industry on the frontend. Ensure that your implementation is optimized for scalability, particularly in handling large datasets.
- [ ] Use [Tailwind CSS](https://tailwindcss.com/) to implement the card design. Refer to the [Figma file](https://www.figma.com/design/9GvGhDV1Te6bQzS1GLoj8J/Dealroom-FE-Assessment?node-id=0%3A1&t=I6Ph4vb2EAvbkQQ7-1) for design specifications.

![Card Design](./assets/card.svg)


---

Good luck with your assignment! Have fun!
