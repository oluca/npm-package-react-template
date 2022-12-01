# NPM Package Template with React

## Workflow

1. Edit ```sh /src/index.js``` file
2. Run ```sh npm run build```

## Test Package Locally

1. Go into root folder of package and run ```shnpm link```
2. Go to your project and run ```shnpm link <package_name>```
3. Implement in your code <br>
```javascript
import Hello from "npm-package-react-template";

export default function Test() {
  return (
    <>
      <Hello />
    </>
  );
}
``` 
