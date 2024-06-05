**Description -** Create a custom domain specific language (DSL), compile the DSL to WebAssembly. Develop a compiler for DSL, deploy the compiled WASM module as microservices and manage them using Kubernetes.

### Key Components:

1. **DSL (Domain-Specific Language)**: Design a simple DSL for a specific domain (e.g., arithmetic operations, string manipulations, or simple algorithms).
2. **Compiler**: Develop a compiler that translates the DSL into WebAssembly.
3. **WASM Microservices**: Create microservices that execute the compiled WASM modules.
4. **Kubernetes**: Use Kubernetes to deploy, scale, and manage the WASM microservices.
5. **Frontend**: Build a frontend to write DSL code, compile it to WASM, and execute the resulting WASM modules through microservices.

## Complete Workflow

![image](https://github.com/Prakhar-Shankar/DSL_to_WASM_Compiler/assets/97254881/a00d4655-23ad-4d44-9666-60a86c872adb)


In this setup:

1. **Frontend**: The user writes DSL code in a text area and clicks a button to compile and execute it.
2. **Server**: The server receives the DSL code, compiles it to WASM using the custom compiler, and deploys the WASM module as a microservice.
3. **Kubernetes**: Kubernetes handles the deployment, scaling, and management of the microservices.
4. **Execution**: The frontend sends requests to the microservices to execute the compiled WASM code and displays the result.
