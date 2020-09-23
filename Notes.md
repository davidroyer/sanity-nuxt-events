# Notes

## Getting Started

- Encountered errors on Netlify builds for initial deployes.  
  I tried using Netlify's **clear cache and retry build** but still same issue.

- My initial attempt to for `npm run dev` produced an error mentioning i need to
  run `sanity login`
  - When following the Nuxt tutorial in the Guides section, nothing mentioned
    about needing to also install the sanity CLI and then login. So before even
    cloning the repo it would have made since to run the following:
    ```bash
    npm i -g @sanity/cli && sanity login
    ```
