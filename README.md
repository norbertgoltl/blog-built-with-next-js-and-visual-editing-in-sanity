# Next.js Blog with Visual Editing in Sanity CMS

🚧 **This project is currently under active development** 🚧

A modern blog application built with Next.js 14, TypeScript, Tailwind CSS and Visual Editing in Sanity CMS.

## Quick Start

1. Clone the repo:
   ```
   git clone https://github.com/norbertgoltl/blog-built-with-next-js-and-visual-editing-in-sanity.git
   cd blog-built-with-next-js-and-visual-editing-in-sanity
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Set up `.env.local`:
   ```
   NEXT_PUBLIC_SANITY_PROJECT_ID=your_sanity_project_id
   NEXT_PUBLIC_SANITY_DATASET=your_sanity_dataset
   SANITY_API_READ_TOKEN=your_sanity_api_token
   ```

4. Run the dev server:
   ```
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000)

6. Access Sanity Studio at [http://localhost:3000/studio](http://localhost:3000/studio)

## Key Features

- Next.js 14 with App Router
- TypeScript
- Sanity CMS integration with Visual Editing
- Tailwind CSS

## Project Structure

- `/app`: Next.js pages and API routes
- `/components`: React components
- `/sanity`: Sanity CMS config and schemas

## Sanity Studio

The Sanity Studio is accessible at the `/studio` route in your browser. Use this to manage your content and take advantage of the visual editing features.

## License

MIT License - see [LICENSE](LICENSE) for details.

---

**Note**: This project is in development. Features may be incomplete or subject to change.
