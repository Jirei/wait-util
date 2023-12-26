Simple utility function to wait:
```ts
export async function wait(ms: number) {
  return new Promise((resolve) => setTimeout(resolve, ms));
}
```