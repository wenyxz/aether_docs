# Aether Documentation

Welcome to the official documentation for **Aether**, a simple app for
completing manual sign-ups easily.

------------------------------------------------------------------------

## 🧊 Blueprint

##### Block Module

-   You can add a block module in **Blueprint** by clicking **Add Block
    Module**.
-   Each block stores **action modules**, which represent individual
    files. You can add them to a block by drag-and-drop from the
    sidebar.
-   Each action can be set as a **PASTE** or **TYPE** action, which
    determines how the specific action will be performed.
-   The current action is automatically set using **Step Forward / Step
    Backward**.
-   Users can manually force a specific current action by clicking on
    it.
-   The current action is marked with an orange border.
-   Block modules can be renamed by double-clicking the block name.
-   Each block module can be assigned a color.
-   **Step Forward**: moves to the next line of the file and inserts the
    data.
-   **Step Backward**: moves back without inserting data.

##### Buttons

-   **Start / Stop Script**
-   **Show / Hide Tracker Window**
-   **Add Block Module**

##### Tracker Window

-   An always-on-top window showing the current data.
-   Can be moved freely by drag-and-drop.
-   Updates in real time.

------------------------------------------------------------------------

## 📝 Notepad

-   By default, when you open file in the Notepad editor, you start on the first
    unused line.
-   **Used lines** are marked with a gray line and gray number. These
    lines **cannot** be edited or removed until you remove them or erase
    all used lines.

##### Buttons

-   **Go to First Unused Line** --- jump directly to the first unused
    line.
-   **Add Used Line**
-   **Remove Used Line**
-   **Erase All Used Lines** --- removes all used line markers.
-   Search bar with **Next / Previous Result** navigation.

------------------------------------------------------------------------

## ⚙️ Settings

Set the window scale manually if necessary.

------------------------------------------------------------------------

## 📁 Projects

##### New Project

-   Opening the Aether app automatically creates the first project.
-   Default location for project folders:
    `../Documents/Aether/Projects/EXAMPLE_PROJECT`
-   Projects can be moved between devices as a project folder.

##### Opening an Existing Project

-   Projects can be opened from any location.
-   To open a project, locate the `.aether` file inside the specific
    project folder.

##### Renaming a Project

-   Double-click the project name in the sidebar to rename it.

------------------------------------------------------------------------

## 📄 File Import

##### TXT Files

Importing a `.txt` file is straightforward.

##### CSV Files

Importing a `.csv` file splits **each column** into a **separate file**,
where the first row becomes the file name and the remaining rows become
the file content.

------------------------------------------------------------------------
