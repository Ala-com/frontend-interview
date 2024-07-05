## Setup

```
yarn
yarn start
```

## Tasks

1. Render the list of results using `<SearchResultItem />` component.
2. Find and fix a bug in the code.
3. Add styling, you can take inspiration from design.png file.
4. Create a hook similar to useQuery/useSWR. It should support custom fetcher functions.
   Example:

```javascript
const { isLoading, error, data } = useQuery("key", () =>
  fetch("https://api.github.com/").then((res) => res.json())
);
```

5. Implement caching fetcher results based on key, cache mutation.
