# Bookshelf-API

Submission for Dicoding: Backend Application for Beginner Course.

### Routes
#### Save Books
- Method : POST
- URL : `/books`
- Body Request:
```
{
    "name": string,
    "year": number,
    "author": string,
    "summary": string,
    "publisher": string,
    "pageCount": number,
    "readPage": number,
    "reading": boolean
}
```

#### Get All Books
- Method : GET
- URL : `/books`
- Query (Optional) :
```
name: string,
reading: boolean,
finished: boolean
```

#### Get One Book
- Method : GET
- URL : `/books/{bookId}`
- Body Request:

#### Edit Book
- Method : PUT
- URL : `/books/{bookId}`
- Body Request:
```
{
    "name": string,
    "year": number,
    "author": string,
    "summary": string,
    "publisher": string,
    "pageCount": number,
    "readPage": number,
    "reading": boolean
}
```

#### Delete Book
- Method : DELETE
- URL : `/books/{bookId}`
- Body Request:

### Others
- Using <b>CORS</b> for all the resources.
- Using ESLint with Airbnb-base Javascript Styling Guide.
