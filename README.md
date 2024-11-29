```markdown
# Architect's Drafting App

Architect's Drafting App is designed to assist architects in creating quick drafts by taking notes and photos, helping them organize ideas for future professional designs. This app uses **Core Data**, an iOS feature, as its database to store and manage the drafts and photos efficiently.

## Features

- **Create Drafts**: Allows architects to add notes and attach relevant photos for their drafts.
- **Core Data Integration**: Uses Core Data to store and manage the drafts and associated data.
- **Detail View**: Displays a detailed view of each draft, allowing for later review and analysis.
- **Simple Interface**: User-friendly interface that makes it easy to add, view, and manage drafts and photos.

## How It Works

1. **Core Data Integration**:
   - Used **Core Data** to create a local database for storing the drafts, photos, and notes.
   - Created functions to add, fetch, and manage the data stored in Core Data.

2. **Interface Design**:
   - Designed an intuitive user interface that allows users to easily input data (notes and photos) and organize drafts.
   - Developed a **detail view** to examine and review each added draft, including associated photos and notes.

3. **Small Details**:
   - Polished the app by adding additional features and refining the interface for an optimal user experience.

## Requirements

- Xcode 14+
- iOS 15+
- Swift 5.7+
- Core Data

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/architect-drafting-app.git
   cd architect-drafting-app
   ```

2. Open the project in Xcode:
   ```bash
   open ArchitectDraftingApp.xcodeproj
   ```

3. Run the project on a simulator or a physical device.

## Video Demo

https://github.com/user-attachments/assets/cb7a9523-8ffa-482f-8174-72d4c3412c1e

## Technologies Used

- **Swift**: Programming language for the project.
- **Core Data**: For managing and storing drafts, photos, and notes.
- **Storyboard**: For designing the app's interface.

## Future Improvements

- Add functionality to organize drafts into different categories or projects.
- Implement cloud synchronization for data backup and sharing across devices.
- Add photo editing or annotation tools to further enhance the drafts.
- Introduce a search feature to easily find specific drafts or notes.
