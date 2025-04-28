# Pokémon Explorer

> This repository is intentionally kept without full source code.

## Why?
> Due to recent incidents where submitted test tasks were reused without hiring or providing feedback, I have decided to protect my work.

> I am happy to share:
> - A fully working **live demo** of the project: [Click here to view the Demo](https://pokemonexplorerbykrishna.netlify.app/)

> If you would like access to the complete source code for evaluation purposes:
> - Please contact me and I can provide private, temporary access through GitHub.

> Thank you for your understanding.

> Best regards,  
> Pavan Krishna D

# Pokémon Data Explorer

An interactive web application that allows users to explore and search through the first 150 Pokémon from the original Pokédex. Built with Next.js, TypeScript, and Tailwind CSS.

![Pokémon Data Explorer](https://images.pexels.com/photos/1716861/pexels-photo-1716861.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2) 

## Features

- 🔍 Real-time search functionality
- 🏷️ Filter Pokémon by type
- 🎨 Beautiful card-based UI design
- 🌓 Light/Dark mode support
- 📱 Fully responsive layout
- ⚡ Fast and efficient data loading
- 🛡️ Type-safe with TypeScript
- 🎭 Smooth animations with Framer Motion

## Technologies

- [Next.js](https://nextjs.org/) - React framework for production
- [TypeScript](https://www.typescriptlang.org/) - Static type checking
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [shadcn/ui](https://ui.shadcn.com/) - Re-usable components
- [Framer Motion](https://www.framer.com/motion/) - Animation library
- [Zod](https://zod.dev/) - TypeScript-first schema validation
- [PokeAPI](https://pokeapi.co/) - RESTful Pokémon API

## Getting Started

### Prerequisites

- Node.js 18.0 or later
- npm or yarn package manager

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pokemon-data-explorer.git
   ```

2. Navigate to the project directory:
   ```bash
   cd pokemon-data-explorer
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage

- **Search**: Type in the search bar to filter Pokémon by name
- **Type Filter**: Use the dropdown to filter Pokémon by their type
- **Theme Toggle**: Switch between light and dark modes using the theme toggle in the header
- **Responsive Design**: Works seamlessly across desktop, tablet, and mobile devices

## Project Structure

```
pokemon-data-explorer/
├── app/
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
├── components/
│   ├── pokemon-explorer.tsx
│   ├── theme-provider.tsx
│   ├── theme-toggle.tsx
│   └── ui/
├── lib/
│   ├── pokemon.ts
│   └── utils.ts
└── public/
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Data provided by [PokeAPI](https://pokeapi.co/)
- UI components from [shadcn/ui](https://ui.shadcn.com/)
- Icons from [Lucide React](https://lucide.dev/)

