# instapic-web

Mini Instagram Webpage

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file (see .env.example)

```
NEXT_PUBLIC_IMAGEKIT_URL=
NEXT_PUBLIC_API_URL=
```

## Running the app

```bash
# development
$ yarn start:dev

# production mode
$ yarn build
$ yarn start
```

## Test

```bash
# unit tests
$ yarn test

# e2e tests
$ yarn test:e2e

# test coverage
$ yarn test:cov
```

## Tech Stack

**Client:** React, Next.js, jest, ImageKit, fontsource, formik, Chakra UI, Axios, React-query

## Lessons Learned

- Build a React webpage from scratch
- Caching
- Using Chakra UI
- Unit testing with jest

## Optimizations

- SSR on homepage
- Real-time image transformation using ImageKit (resize and webp)
- Caching some results with react-query
