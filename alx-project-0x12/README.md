## alx-project-0x12

# custom hooks

## 🎯 Objective

Make the code cleaner, easier to maintain, and reusable by extracting the image generation logic (`handleGenerateImage`) into a custom hook.

1. **Create** a new custom hook file named `useImageGenerator.ts` inside the `hooks/` directory.

2. **Move** the `handleGenerateImage` logic from `pages/index.tsx` into this custom hook.

3. **Encapsulate** the API call logic and loading state within the custom hook.

4. **Return** the necessary values and functions from the hook (e.g., `generateImage`, `imageUrl`, `isLoading`).

5. **Import and use** the custom hook inside `pages/index.tsx`.

6. **Replace** the existing `handleGenerateImage` logic with the function returned from the hook.
