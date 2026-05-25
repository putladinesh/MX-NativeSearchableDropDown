# Native Searchable Dropdown Widget Documentation

## Description

The **Native Searchable Dropdown** widget allows developers to search and select a single object in Mendix Native applications using a mobile-friendly searchable dropdown interface. The widget is specifically designed to work with **1-to-Many associations**, enabling users to easily select and manage associated objects through search functionality.

The widget provides a clean and efficient user experience for selecting objects from a datasource while supporting dynamic display values and change event handling.

## Typical Usage Scenarios

- Allow users to search and select related objects in Native Mobile applications.
- Manage associations using a user-friendly searchable dropdown.
- Improve usability when working with large datasets in Native applications.
- Trigger business logic dynamically when selections are updated.
- Use in assignment screens, lookup forms, approval workflows, and object selection screens.

## Features

### 1. Searchable Dropdown
- Allows users to dynamically search objects inside the dropdown list.

### 2. Association Support
- Supports selecting associated objects using Mendix associations.

### 3. Dynamic Display Name
- Configure the attribute that should be displayed inside the dropdown list.

### 4. On Change Event
- Trigger actions whenever the selected value changes.


## Setup

### Required Properties

### 1. Label
- Defines the label displayed above the dropdown.

### 2. Reference
- Configure the association used to store the selected object.

### 3. Selectable Objects
- Configure the datasource containing the selectable objects.

### 4. Display Name
- Select the attribute that should be shown inside the dropdown list.

### 5. On Change
- Optional action triggered whenever the selected value changes.

## Dependencies

- No Dependencies

## Installation

### Steps:

1. **Import the widget** into your Mendix project.
2. **Place the widget** inside a Native Mobile page.
3. **Configure the properties**:
   - Label
   - Reference association
   - Selectable Objects datasource
   - Display Name attribute
   - On Change action (optional)
4. **Run the application**.
5. **Search and select objects** dynamically from the dropdown.

## Bugs

- **No bugs have been reported so far.**
- If any bugs are found, please add them in the reviews section.
