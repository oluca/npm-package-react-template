# NPM Package Template with React

## Workflow

1. Edit `/src/index.js` file
2. Run `npm run build`

## Test Package Locally

1. Go into root folder of package and run `npm link`
2. Go to your project and run `npm link <package_name>`
3. Implement in your code <br>
`import Hello from "npm-package-react-template";

export default function Test() {
  return (
    <>
      <Hello />
    </>
  );
}
`javascript
