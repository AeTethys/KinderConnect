# KinderConnect
KinderConnect's Demo App

A comprehensive web application for managing preschool operations, including student information, class management, attendance tracking, parent communication, and educational resources.

## Features

- User Management**: Different access levels for administrators, teachers, and parents
- Student Management**: Complete student profiles with personal, medical, and contact information
- Class Management**: Create and manage classes, assign students and teachers
- Attendance Tracking**: Record and monitor student attendance
- Parent Communication**: Messaging system for parent-teacher communication
- Calendar**: School events and schedule management
- Educational Resources**: Upload and share educational materials
- Progress Tracking**: Monitor student development and learning objectives
- Reporting & Analytics**: Generate insights from school data


## Technologies Used

- Next.js (App Router)
- React
- TypeScript
- Tailwind CSS
- Supabase (Authentication & Database)


## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- Supabase account


### Installation

1. Clone the repository

```shellscript
git clone https://github.com/yourusername/school-management-system.git
cd school-management-system
```


2. Install dependencies

```shellscript
npm install
# or
yarn install
```


3. Set up environment variables
Create a `.env.local` file in the root directory with the following variables:

```plaintext
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
SUPABASE_SERVICE_ROLE_KEY=your_supabase_service_role_key
```


4. Run the development server

```shellscript
npm run dev
# or
yarn dev
```


5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application


## Project Structure

```plaintext
├── app/                  # Next.js App Router
│   ├── api/              # API routes
│   ├── dashboard/        # Dashboard pages
│   ├── login/            # Authentication pages
│   └── ...
├── components/           # React components
├── contexts/             # React contexts
├── hooks/                # Custom React hooks
├── lib/                  # Utility functions
├── public/               # Static assets
├── services/             # Service layer for API calls
└── types/                # TypeScript type definitions
```

## Deployment

This application can be deployed on Vercel:

1. Push your code to a GitHub repository
2. Connect your repository to Vercel
3. Configure environment variables in Vercel dashboard
4. Deploy


## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Supabase](https://supabase.io/)
- [shadcn/ui](https://ui.shadcn.com/)
