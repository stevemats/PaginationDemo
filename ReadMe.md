# FastAPI Pagination Demo

FastAPI project demo. Modify it to use on other projects.

The _*data.Json*_ demo data was gotten from => [jsonplaceholder.typicode.com](https://jsonplaceholder.typicode.com/posts)

---

## Requirements:

- [FastAPI](https://fastapi.tiangolo.com/) => pip install fastapi
- [Uvicorn](https://www.uvicorn.org/) => pip install "uvicorn[standard]"
- [Repo clone](https://github.com/stevemats/PaginationDemo) => git clone https://github.com/stevemats/PaginationDemo.git

---

## Usage:

On your terminal, navigate to project folder and run below commands:

Run the api in dev mode:

    uvicorn main:app --reload

or

    python -m uvicorn main:app --reload

Access the Json Data:

    http://127.0.0.1:8000/posts

Access the Interactive Documentation:

    http://127.0.0.1:8000/docs

![interactive](https://user-images.githubusercontent.com/30528167/161042323-f7c52df7-a75c-4534-9bab-9c01efebf6f0.png)

Alternate Documentation:

    http://127.0.0.1:8000/redoc

![fastapi](https://user-images.githubusercontent.com/30528167/161041617-975dcc6a-1b78-46b0-8561-3a6751be65c7.png)

---
