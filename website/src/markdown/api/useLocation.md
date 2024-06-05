# useLocation

Returns the location to any component.

This API requires a hook-compatible version of React.

```jsx
import { useLocation } from "@nx-pkg/reach-router"

const useAnalytics = (props) => {
  const location = useLocation();

  useEffect(() => {
    ga.send(['pageview', location.pathname]);
  }, [])
)
```
