# cypress/base:12.1.0

## Example

Sample Dockerfile

```
FROM cypress/base:12.1.0
RUN npm install --save-dev cypress
RUN $(npm bin)/cypress verify
RUN $(npm bin)/cypress run
```
