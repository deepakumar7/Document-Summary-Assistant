# Document-Summary-Assistant

Document Summary Assistant is a web application that allows users to upload documents and generate summarized versions. The project is built using modern web development technologies and provides a user-friendly interface for document management.

![image](https://github.com/user-attachments/assets/ab6e74db-61eb-411a-9a84-a9f59e5beedc)


## Features

- Upload PDF documents.
- Generate short or detailed summaries of uploaded documents.
- User-friendly interface.

## Technology Stack

### Frontend
- **HTML**
- **CSS**
- **JavaScript**
- **React.js**

### Backend
- **Node.js**
- **Express.js**



## Prerequisites

Ensure you have the following installed:
- Node.js (v18.16.0 or later)
- Git

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/document-summary-assistant.git
   cd document-summary-assistant
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```
   The application will be accessible at `http://localhost:5000`.

4. Build the project for production:
   ```bash
   npm run build
   ```


   ```

## Common Issues

### 404: NOT_FOUND Error
- Ensure that API routes are correctly defined in `pages/api/`.
- Verify that the frontend is pointing to the correct API endpoint.
- Check deployment logs in Vercel for any errors.

### MODULE_NOT_FOUND Error
- Ensure all required dependencies are installed by running `npm install`.
- Verify the `package.json` file for missing or incorrect dependencies.

## Folder Structure

```
project-root/
├── file/                 # Contains uploaded documents
├── node_modules/         # Project dependencies
├── pages/                # Next.js pages
│   ├── api/              # API routes
│   └── index.js          # Main frontend page
├── public/               # Static files
├── .gitignore            # Git ignore rules
├── package.json          # Project metadata and scripts
└── README.md             # Project documentation
```

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push to your fork:
   ```bash
   git push origin feature-name
   ```
4. Submit a pull request to the main repository.



## Contact

For any questions or feedback, feel free to contact:
- **Name:** Deepak Kumar
- **GitHub:** [deepakumar7](https://github.com/deepakumar7)
-


