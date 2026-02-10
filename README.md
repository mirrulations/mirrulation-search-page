
## How to run it
1. npm install
2. npm run dev

## Differences

- Only major change that is different from the mirrulation-website repo was deleting the useEffect below, and changing imports for the styling. Obviously I have massive changes with the css and other stuff.

```
useEffect(() => {
  const isAuthenticated =
    localStorage.getItem("isAuthenticated") === "true";

  if (!isAuthenticated) {
    navigate("/auth");
  }
}, [navigate]);
```
