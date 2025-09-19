# Is in browser DOCX editing possible with react
This repository contains an example of how to achieve in-browser DOCX editing in a React application using the Syncfusion DOCX Editor. It showcases rich Word document (DOCX) editing and rendering directly within the browser, entirely free from Microsoft Word or Office interop dependencies.

# How to run the application

1.  **Clone the repository** to your local machine.

2.  **Install Dependencies**
    Install the required npm packages for the project.
    ```bash
    npm install
    ```

3.  **Run the Web Service**
    The Syncfusion Document Editor requires a server-side backend for processing Word documents. You can run the web service from either of the following sources:
    *   **GitHub Source:** Clone and run the [ASP.NET Core Web Service example](https://github.com/SyncfusionExamples/EJ2-Document-Editor-Web-Services).
    *   **Docker Image:** Use the pre-built [Docker image](https://hub.docker.com/r/syncfusion/word-processor-server).

    Once your web service is running, update the `serviceUrl` property in `src/App.tsx` to point to its endpoint.

    ```typescript
    // In src/App.tsx
    <DocumentEditorContainerComponent 
        serviceUrl="http://localhost:62869/api/documenteditor/" 
        height={'100vh'}
        enableToolbar={true} 
    />
    ```

4.  **Run the Application**
    Start the React development server.
    ```bash
    npm start
    ```
    This will open the application in your default web browser, typically at `http://localhost:3000`.


  # Resources 

- **Product page:**   [Syncfusion® React Word Processor](https://www.syncfusion.com/docx-editor-sdk/react-docx-editor) 

- **Documentation:**   [Syncfusion® Word Processor](https://help.syncfusion.com/document-processing/word/word-processor/react/getting-started) 

- **Online demo:**   [Syncfusion® Word Processor - Demo](https://ej2.syncfusion.com/react/demos/) 

# Support and feedback 

For any other queries, reach our [Syncfusion® support team](https://support.syncfusion.com/?utm_source=github&utm_medium=listing&utm_campaign=github-github-documenteditor-examples) or post the queries through the [community forums](https://www.syncfusion.com/forums?utm_source=github&utm_medium=listing&utm_campaign=github-github-documenteditor-examples). 

Request new feature through [Syncfusion® feedback portal](https://www.syncfusion.com/feedback?utm_source=github&utm_medium=listing&utm_campaign=github-github-documenteditor-examples). 

# License

This is a commercial product and requires a paid license for possession or use Syncfusion's licensed software, including this component, is subject to the terms and conditions of [Syncfusion's EULA](https://www.syncfusion.com/license/studio/22.2.5/syncfusion_essential_studio_eula.pdf?utm_source=github&utm_medium=listing&utm_campaign=github-github-documenteditor-examples). You can purchase a licnense [here](https://www.syncfusion.com/sales/products?utm_source=github&utm_medium=listing&utm_campaign=github-github-documenteditor-examples) or start a free 30\-day trial [here](https://www.syncfusion.com/account/manage-trials/start-trials?utm_source=github&utm_medium=listing&utm_campaign=github-github-documenteditor-examples). 
