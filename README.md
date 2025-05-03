# Angular JSON Forms Project

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.2.11.

## 🚀 Project Overview
A dynamic form generator using Angular 15, JSON Forms, and Tailwind CSS that demonstrates:
- JSON-driven UI generation
- Custom form controls
- Responsive layouts
- Real-time validations
- Interactive components

## 📋 Phased Implementation Details

### Phase 1: Project Setup
- **Angular 15** project scaffolding with routing
- **Dependencies**: 
  - `@jsonforms/core` & `@jsonforms/angular`
  - Tailwind CSS v3 with PostCSS
- **Project Structure**:
  - Modular components for forms/renderers
  - Core services for form handling

### Phase 2: JSON Forms Implementation
- **Dynamic Forms** from JSON configurations:
  - 2+ schema layouts (`form-schema1.json`, `form-schema2.json`)
  - Vertical/Horizontal layouts demonstration
- **Schema Switching** through UI buttons
- **Core Features**:
  - Data binding
  - Basic validations

### Phase 3: Custom Renderers
- **Email Renderer**:
  - Custom Angular component
  - Tailwind-styled input
  - Format validation (`format: "email"`)
- **Renderer Registration**:
  - Integrated with default renderers
  - Priority-based tester implementation

### Phase 4: Responsive Design
- **Mobile-First Approach**:
  - Grid layouts (`grid-cols-1 md:grid-cols-2`)
  - Flexible spacing (`space-y-6`, `gap-4`)
- **Tailwind Components**:
  - Card-style containers
  - Interactive buttons
  - Consistent form controls

### Phase 5: Validations & Interactions
- **JSON Schema Validations**:
  - Required fields
  - Minimum lengths
  - Email format
- **Country-City Dropdown**:
  - Dynamic options loading
  - Conditional field visibility
  - Enum-based selections

### Phase 6: Finalization & Deployment
- **Documentation**:
  - Comprehensive README
  - Code comments
  - TypeScript interfaces
- **Quality Assurance**:
  - Linting (`ng lint`)
  - Production build
  - GitHub CI pipeline
- **Demo**:
  - Recorded functionality walkthrough
  - Mobile/desktop testing proof

## 🛠️ Setup Instructions

1. **Clone Repository**
   ```bash
   git clone https://github.com/<your-username>/angular-jsonforms.git
   cd angular-jsonforms
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Run Development Server**
   ```bash
   ng serve
   ```

4. **Access Application**
   Open your browser and navigate to ` http://localhost:4200  ```


## 📄 JSON Structure
Location: src/assets/schemas/

#### Layout 1 (form-schema1.json):

Text input + Email field

Basic validations

#### Layout 2 (form-schema2.json):

Number + Boolean fields

Horizontal layout

#### Layout 3 (form-schema3.json):

Country-City dropdowns

Dynamic field dependencies

## 🧠 Assumptions
Angular CLI v15+ installed globally

Basic understanding of JSON Schema

Familiarity with Tailwind CSS class system

Node.js v18+ runtime environment

## Development server
Run ng serve for a dev server. Navigate to http://localhost:4200/. The application will automatically reload if you change any of the source files.

## Code scaffolding
Run ng generate component component-name to generate a new component. You can also use ng generate directive|pipe|service|class|guard|interface|enum|module.

#### Build
Run ng build to build the project. The build artifacts will be stored in the dist/ directory.

#### Running unit tests
Run ng test to execute the unit tests via Karma.

#### Running end-to-end tests
Run ng e2e to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

#### Further help
To get more help on the Angular CLI use ng help or go check out the Angular CLI Overview and Command Reference page.


#### This structure:
1. Maintains original Angular CLI docs
2. Adds project-specific implementation details
3. Organizes information in logical sections
4. Uses emojis for visual scanning
5. Provides clear setup/usage instructions
6. Documents architectural decisions
7. Links technical implementation to business requirements

#### Key improvements over standard README:
- Clear mapping between requirements and implementation
- Self-documenting architecture
- Onboarding guide for new developers
- Maintenance context for future updates
- Demo preparation checklist
