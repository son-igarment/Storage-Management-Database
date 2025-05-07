# Storage Management Database

## Project Overview
A comprehensive storage management solution developed by Phạm Lê Ngọc Sơn. This application allows users to efficiently organize, manage, and secure their digital assets with a modern, user-friendly interface.

## Features
- **File Organization**: Categorize and store files efficiently
- **User Authentication**: Secure login with OTP verification
- **Dashboard Analytics**: Visual representation of storage usage
- **File Search**: Quick search functionality to find files
- **Mobile Responsive**: Fully functional on all device sizes
- **File Uploads**: Easy drag-and-drop file uploading

## Project Structure
```
Storage-Management-Database/
├── app/                  # Next.js app directory
│   ├── (auth)/           # Authentication routes
│   ├── (root)/           # Main application pages
│   ├── layout.tsx        # Root layout component
│   └── globals.css       # Global styles
├── components/           # Reusable UI components
│   ├── ui/               # Shadcn UI components
│   ├── ActionDropdown.tsx  # File action menu
│   ├── Chart.tsx         # Analytics visualization
│   └── ...               # Other components
├── lib/                  # Utility functions and services
├── constants/            # Application constants
├── public/               # Static assets
└── types/                # TypeScript type definitions
```

## Technology Stack
- **Frontend**: Next.js 15, React 19, TypeScript
- **Styling**: TailwindCSS
- **UI Components**: Radix UI, Shadcn UI
- **Forms**: React Hook Form, Zod validation
- **Charts**: Recharts
- **Backend Integration**: Appwrite

## Getting Started

### Prerequisites
- Node.js (v16 or newer)
- npm or yarn

### Installation
1. Clone the repository
   ```
   git clone [repository-url]
   cd Storage-Management-Database
   ```

2. Install dependencies
   ```
   npm install
   ```
   or
   ```
   yarn
   ```

3. Start the development server
   ```
   npm run dev
   ```
   or
   ```
   yarn dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Usage
1. **Authentication**: Register or log in to access your storage
2. **Dashboard**: View storage analytics and recent files
3. **File Management**: Upload, organize, search, and manage files
4. **Settings**: Configure your storage preferences

## Development
- `npm run build` - Create production build
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Author
- **Phạm Lê Ngọc Sơn**

## License
This project is proprietary and belongs to Phạm Lê Ngọc Sơn.
