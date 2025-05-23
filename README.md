<h1 align="center">Movie list</h1>

<div align="center">
  <table>
    <tr>
      <td>
        <img alt="Dark mode version of user interface. List containg movies with their respective scores." src="https://github.com/user-attachments/assets/98b5a65d-e49d-4597-8ee1-ebe2e19e8080">
      </td>
      <td>
        <img alt="Light mode version of user interface. List containg movies with their respective scores." src="https://github.com/user-attachments/assets/8ac01dcf-f19a-4011-b51d-d431ca26570c">
      </td>
    </tr>
    <tr>
      <td>
        <p>Dark mode</p>
      </td>
        <td>
        <p>Light mode</p>
      </td>
    </tr>
  </table>
</div>

## Overview
Movielist is a web app that allows the user to locally save a collection of movies with associated ratings. Saved movies can be sorted by rating or by name. 

## Project structure
```
.
├── app          # Webpage routes
├── components   # Reusable components
│   ├── icons    # SVG icon components
│   └── ui       # Shadcn UI components
├── lib          # Utility functions
└── types        # Shared TypeScript types
```

### Technologies used

| Name                                           | Description                          |
|------------------------------------------------|--------------------------------------|
| [Next.js](https://nextjs.org/)                 | Full-stack JavaScript framework      |
| [Shadcn UI](https://github.com/shadcn-ui/ui)   | UI component library                 |
| [Tailwind](https://tailwindcss.com/)           | CSS styling library                  |

## Setup

### NPM

> Prerequisite: [Node.js](https://nodejs.org/)

1. Run `npm install` to install dependencies
2. Run `npm run dev` to start the development server
3. Open [http://localhost:3000](http://localhost:3000)

### Docker
> Prerequisite: [Docker](https://www.docker.com/)

1. Run `docker compose up`
2. Open [http://localhost:3000](http://localhost:3000)
