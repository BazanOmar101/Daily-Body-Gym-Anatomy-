# Daily Body Gym Anatomy

An interactive web application that helps users explore muscle anatomy and discover targeted exercises. This mobile-friendly app allows users to select muscles on a body map and see which exercises target those specific muscle groups.

## Features

- **Interactive Body Map**: Click on muscle groups to filter exercises
- **Exercise Database**: Comprehensive list of exercises with difficulty levels and equipment requirements
- **Search Functionality**: Search exercises by name or muscle group
- **Detailed Exercise Information**: View descriptions, primary/secondary muscles, and equipment needed
- **Visual Feedback**: Muscles highlight based on selected exercises
- **Responsive Design**: Works on desktop and mobile devices

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd Daily-Body-Gym-Anatomy-
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:3000`

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

## How to Use

1. **Select a Muscle**: Click on any muscle group in the body map to filter exercises
2. **Browse Exercises**: View the filtered list of exercises that target the selected muscle
3. **Search**: Use the search bar to find specific exercises or muscle groups
4. **View Details**: Click on any exercise to see detailed information including:
   - Exercise description
   - Primary and secondary muscles targeted
   - Difficulty level
   - Required equipment
5. **Visual Feedback**: When you select an exercise, the body map will highlight which muscles are targeted

## Technology Stack

- **React 18** - Frontend framework
- **Vite** - Build tool and development server
- **Tailwind CSS** - Utility-first CSS framework
- **Lucide React** - Icon library
- **SVG** - For interactive body map

## Project Structure

```
src/
├── components/
│   └── MuscleExerciseMapper.jsx  # Main component
├── App.jsx                       # App wrapper
├── main.jsx                      # Entry point
└── index.css                     # Global styles
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.

## Future Enhancements

- Add workout tracking functionality
- Include exercise videos/demonstrations
- Add user accounts and progress tracking
- Implement workout plan generation
- Add more detailed muscle anatomy information
