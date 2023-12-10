# EASY Elementor Loop Grid JavaScript Filtering



https://github.com/mayurjobanputra/EASY-Elementor-Loop-Grid-Javascript-Filtering/assets/6332663/d59f43a8-a508-4ff9-b925-18e738c556f3



This repository contains a simple yet powerful JavaScript solution designed to enhance the functionality of Elementor loop grids. The script enables dynamic filtering of Elementor loop grid items based on user input, providing a seamless and interactive experience.

## Features

- **Dynamic Filtering**: Allows users to filter grid items in real-time by typing into a text input field. The grid updates as the user types, showing only the items that match the entered text.
- **Automatic Item Count**: A display that updates to show the number of visible items versus the total number of items in the grid.
- **MutationObserver Integration**: Utilizes MutationObserver to detect and respond to changes in the DOM, ensuring the item count is always accurate, even when new items are dynamically added to the grid.
- **Responsive UI Elements**: Styled and positioned elements for a clean and intuitive user interface. The filtering input and item count display are neatly laid out for ease of use.
- **Load More Compatibility**: Works in conjunction with Elementor's "Load More" functionality, automatically resetting the filter and updating the item count when new items are loaded.

## How It Works

The script uses jQuery for DOM manipulation and event handling. It observes changes in the loop grid container, updates the item count accordingly, and filters grid items based on the user's input. The filter works by comparing the lowercased text of each grid item against the lowercased input value, providing a case-insensitive match.

## Usage Instructions

1. **Code Placement**: Insert the entire provided code above any page that contains a loop grid. The ideal approach is to use an Elementor template. Once you have created your template, use the Elementor template embed code to insert this into a shortcode.
   
2. **Compatibility Note**: This script is designed for use with Elementor Pro. It has not been tested with the free version of Elementor, so compatibility is not guaranteed with the free version.

3. **Filtering Trigger**: The script is configured to trigger the filtering process 1 second after the user stops typing. This ensures a smoother user experience without overwhelming instant changes.

4. **Pagination Compatibility**: Successfully tested with Elementor's pagination feature, including the "Load More" button. However, it has not been tested with infinite scroll, so its functionality in such scenarios remains unverified.

5. **Troubleshooting**: If you encounter any issues with the script, you can seek assistance:
    - Ensure that your Elementor Pro version is up to date.
    - Double-check that the script is correctly placed as per the instructions.
    - If problems persist, consider seeking help by using ChatGPT. Provide the HTML of your page and ask for specific input or troubleshooting steps regarding the issue.

This repository is perfect for Elementor users looking to add interactive and user-friendly filtering to their loop grids. It's easy to implement and doesn't require extensive JavaScript knowledge.
