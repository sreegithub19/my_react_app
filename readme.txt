JS -> TS:
    1. Add tsconfig.json
    2. npm i --save-dev @types/react
    3. npm i --save-dev @types/react-dom
    4. There is a react-app-env.d.ts file in your src folder. If you don't see it, create a new file in the src folder named react-app-env.d.ts.
            Now in your react-app-env.d.ts, add this code.

                        declare module "*.png";
                        declare module "*.svg";
                        declare module "*.jpeg";
                        declare module "*.jpg";

    