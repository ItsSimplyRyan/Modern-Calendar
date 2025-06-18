# Modern Calendar App

A beautiful, modern calendar application built with Next.js, React, and Tailwind CSS. This application provides an intuitive interface for managing events, meetings, and appointments with a stunning visual design.

## 🌟 Features

- **Modern UI/UX**: Beautiful glassmorphism design with backdrop blur effects
- **Week View Calendar**: Interactive weekly calendar layout with time slots
- **Event Management**: Create, view, and manage calendar events
- **Multiple Calendars**: Support for different calendar categories (Work, Personal, Family, etc.)
- **Event Details**: Rich event information including location, attendees, and descriptions
- **Responsive Design**: Optimized for desktop and mobile devices
- **Dark/Light Theme Support**: Built-in theme switching capability
- **Search Functionality**: Quick search through events and calendars
- **Mini Calendar**: Quick month overview in the sidebar

## 🛠️ Tech Stack

- **Framework**: Next.js 15.2.4
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: Radix UI
- **Icons**: Lucide React
- **Date Handling**: date-fns, react-day-picker
- **Forms**: React Hook Form with Zod validation
- **Package Manager**: pnpm

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (version 18 or higher)
- pnpm (recommended) or npm

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd Modern-Calendar
```

### 2. Install Dependencies

```bash
# Using pnpm (recommended)
pnpm install

# Or using npm
npm install
```

### 3. Run the Development Server

```bash
# Using pnpm
pnpm dev

# Or using npm
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### 4. Build for Production

```bash
# Using pnpm
pnpm build
pnpm start

# Or using npm
npm run build
npm start
```

## 📁 Project Structure

```
Calendar/
├── app/                    # Next.js app directory
│   ├── layout.tsx         # Root layout component
│   ├── page.tsx           # Main calendar page
│   ├── loading.tsx        # Loading component
│   └── globals.css        # Global styles
├── components/            # Reusable components
│   └── theme-provider.tsx # Theme context provider
├── lib/                   # Utility functions and configurations
├── public/                # Static assets
├── styles/                # Additional stylesheets
└── package.json           # Project dependencies and scripts
```

## 🎨 Customization

### Styling
The application uses Tailwind CSS for styling. You can customize the design by modifying:
- `tailwind.config.js` - Tailwind configuration
- `app/globals.css` - Global styles and custom CSS
- Component-specific styles in individual files

### Themes
The app includes theme support through `next-themes`. You can customize themes by modifying the theme provider in `components/theme-provider.tsx`.

## 📦 Available Scripts

- `pnpm dev` - Start development server
- `pnpm build` - Build for production
- `pnpm start` - Start production server
- `pnpm lint` - Run ESLint

## 🌐 Deployment

The application is configured for easy deployment on Vercel:

1. Push your code to a Git repository
2. Connect your repository to Vercel
3. Deploy automatically on every push

### Manual Deployment

```bash
# Build the application
pnpm build

# Start the production server
pnpm start
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🔗 Links

- **Live Demo**: []()
- **Development**: []()

## 📞 Support

If you encounter any issues or have questions, please open an issue in the repository or contact the development team.