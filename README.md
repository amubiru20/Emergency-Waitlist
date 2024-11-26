# Hospital Triage App Design System

## **1. Fonts**
### **Fonts Used**
- **Primary Font:** Open Sans
  - Weights: Regular (400), Semi-bold (600)
  - Usage: Used consistently across all pages for a clean and professional look.

### **Font Rationale**
- Open Sans provides a modern and clean aesthetic, ensuring readability for both users and administrators.

---

## **2. Color Palette**
| Section              | Color             | Hex Code  | Purpose                                 |
|----------------------|-------------------|-----------|-----------------------------------------|
| Background (User)    | White             | #FFFFFF   | Clean, minimal base for clarity.        |
| Background (Admin)   | Light Gray        | #F3F3F3   | Differentiates admin panel visually.    |
| Primary (Header)     | Blue              | #007BFF   | Highlights titles and important buttons.|
| Accent (Header Admin)| Orange            | #FF9900   | Represents urgency and administrative tasks.|
| Danger Buttons       | Red               | #DC3545   | For removing or critical actions.       |

---

## **3. App Components**
### **User Page**
#### **Form**
- **Injury Types**: Head, Heart, Lung, Neck, Stomach, Bone or Muscle, Burn or Cut.
- **Pain Levels**: Rated from 1 (Not Bad) to 10 (Unbearable).

#### **Design Choices**
- **Form Layout**: Vertical stack for ease of navigation.
- **Button Design**: Primary button styled in blue with hover effects for a modern touch.

---

### **Admin Page**
#### **Table**
- Columns: Entry Number, Necessary Attention, Injury Type, Pain Level.
- Features: Editable rows with actions (e.g., remove or adjust attention level).

#### **Action Buttons**
- **Remove from Triage**: Red button to delete entries.
- **Adjust Attention**: Buttons to increase or decrease necessary attention levels.

#### **Design Choices**
- **Header Styling**: Orange header differentiates it from the User Page.
- **Table Layout**: Simplified and responsive, making it easy to manage data.

---

## **4. Layout and Navigation**
### **User Page**
- **Title**: "Hospital Triage - User Page" prominently displayed.
- **Form**:
  - Top Section: Dropdowns for injury type and pain level.
  - Bottom Section: Submit button centered.

### **Admin Page**
- **Title**: "Hospital Triage - Admin Page" styled in orange.
- **Table**:
  - Lists triage entries with fields for necessary attention, injury type, and pain level.
- **Actions**:
  - Buttons for entry management below the table.

---

## **5. Consistency**
- **Typography**: Open Sans used across both pages.
- **Color Palette**: Unified scheme for buttons and headers.
- **Forms and Buttons**: Consistent padding, font size, and hover effects.

---

## **6. Visual Aids**
### User Page
- Title: Hospital Triage - User Page.
- Form: Dropdowns for injury types and pain levels.
- Submit button styled in blue.
![Screenshot 2024-11-26 175237](https://github.com/user-attachments/assets/9f1b2772-9ea1-4234-b711-43848b195da6)


### Admin Page
- Table: Organized data for triage management.
- Action Buttons: Red for critical actions.
![Screenshot 2024-11-26 175256](https://github.com/user-attachments/assets/f3cc02bf-456f-4f13-ac77-202fdf3f6ba0)



---


## **References**
- [Markdown Guide](https://www.markdownguide.org/cheat-sheet/)
- [Design System Inspiration](https://github.com/kvhuang23/cst3106_labs/blob/236d6e01304896696d0514b230eb1cf4a450153f/lab10/hospital_triage_design_system.md)

