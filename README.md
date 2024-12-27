# Next.js Nested Directory Server-Side Props Error

This repository demonstrates a bug in Next.js related to using server-side props (getStaticProps or getServerSideProps) within nested directory structures.  The issue manifests as unexpected behavior or 404 errors when attempting to access pages with dynamic segments within nested directories.

## Bug Description

The bug occurs when using dynamic segments in a nested directory structure.  The routing might conflict, leading to incorrect pages being rendered or 404 errors.

## How to Reproduce

1. Clone this repository.
2. Install dependencies using `npm install`.
3. Run the development server using `npm run dev`.
4. Try accessing the nested routes.  You'll observe unexpected behavior or 404 errors.

## Solution

The solution involves carefully structuring the directories and routes to resolve the conflicts. This may involve restructuring your directory, using different route structures, or refining your server-side props logic to correctly handle the nested dynamic segments.