# SS-Data Explorer Documentation

This documentation provides access to a collection of user journey demonstrations across various websites and applications. Each demonstration captures detailed user interactions and behaviors in a structured format.

## Dataset Structure

The dataset consists of numerous demonstration files in Markdown format, each representing a specific user journey or interaction flow. Files are named using the following convention:

`id={ID}_demo={DEMO_NUMBER}.md`

Where:
- `ID`: A unique numeric identifier for the demonstration (e.g., 359, 326)
- `DEMO_NUMBER`: Usually 0, allows for multiple demonstrations of the same scenario

## Content Format

Each demonstration file follows a consistent structure:

### 1. Task Description
- Title of the task
- User story format (As a..., I..., so that...)
- Clear success definition

### 2. Trajectory
- Step-by-step breakdown of the user journey
- For each step:
  - URLs (before and after the action)
  - Page content and state changes
  - Detailed DOM structure and accessibility information
  - Interactive elements and their properties

### 3. Technical Details
- DOM structure
- Accessibility tree information
- Interactive elements (links, buttons, forms)
- Page state changes

## File Organization

The demonstrations are stored in the `docs/` directory, with each file representing a complete user journey. The collection covers a wide range of websites and user interactions, from simple navigation to complex form submissions.

## Usage

This documentation serves as a valuable resource for:
- Understanding user interaction patterns
- Analyzing website behavior and structure
- Studying accessibility implementations
- Examining DOM state changes during user interactions
