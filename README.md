# Frontend template 
#### Initial
1. Component
    ###### Init common components : ( with animation )
     - buttons ( primary, secondary ) 
     - links ( internal, external )
     - heading ( h1, h2, h3, ... ) 
     - select, dropdown
    ###### Module component: 
    - create all component when use >= 2 times in the main components folder
    - create component usee only 1 time in folder of that component
2. Code rule
    -- Write description with all function not a components
    -- Remove all warning in console, maybe have some warning in console.
    ...
3. folder structure
.
├── public
├── src
│   ├── components
│   │   └── buttons
│   │       └── PrimaryButton.tsx
│   │       └── SecondaryButton.tsx
│   ├── hooks
│   │   └── useQuery.ts
│   │   └── usePagination.ts
│   ├── constants
│   │   └── error.ts
│   │   └── role.ts
│   ├── lib
│   │   └── clsxm.ts
│   │   └── logger.ts
│   │   └── helper.ts
│   ├── pages
│   │   └── ...
│   ├── screens
│   │   └── home
│   │       └── components
│   │           └── HomeSpecialButton.tsx
│   │       └── index.tsx
│   │   └── about-us
│   │       └── components
│   │           └── AboutUsSpecialButton.tsx
│   │       └── index.tsx
│   ├── style
│   │   └── global.css
├── ...