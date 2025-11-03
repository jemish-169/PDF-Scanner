# Pro Scanner

## Features
- **Scan Documents**: Easily scan documents and save them in both internal and external storage with appropriate permissions.
- **Swipe to Delete**: Users can delete PDF files with a simple swipe gesture.
- **Save as Images**: Save PDF pages as images in external storage for easy access and sharing.
- **Manage PDF Files**: Rename, share, and delete PDF files directly within the app.
- **Auto Scan and Edge Detection**: Utilize ML Kit's document scanner library for automatic scanning and edge detection.
- **Categorize Files**: Organize scanned files by selecting categories, which internally create directories for better management.

## Live Demo

Get the Pro scanner app from Google Play: [https://play.google.com/store/apps/details?id=com.elite.scanner](https://play.google.com/store/apps/details?id=com.elite.scanner)

## Technology
- **Android with Jetpack Compose**: Utilizes modern Android development tools to create a sleek and responsive UI.
- **MVVM Architecture**: Ensures a modular, testable, and maintainable code structure.

### Directory Structure
- When a user creates a category and saves a file in it, a directory with the same name is created internally to store the PDF file.
- Saving images of PDF pages creates another external directory for easy access and organization.

## Screenshots  

<table>
  <tr>
    <td align="center"><b>Home Screen</b><br><img src="https://github.com/user-attachments/assets/f9a4ecd2-8e38-4244-81f3-1451dc2e6564" width="250"/></td>
    <td align="center"><b>Rename and/or Change Category</b><br><img src="https://github.com/user-attachments/assets/1217b112-4f20-43ca-929d-e0801a74bd55" width="250"/></td>
    <td align="center"><b>Multiple Select</b><br><img src="https://github.com/user-attachments/assets/d0e54b8b-a251-408c-a725-a3e997579c00" width="250"/></td>
  </tr>
  <tr>
    <td align="center"><b>Scan / Upload Document</b><br><img src="https://github.com/user-attachments/assets/f6263ed9-1df7-440f-b886-4b191991b650" width="250"/></td>
    <td align="center"><b>Retouch Document</b><br><img src="https://github.com/user-attachments/assets/f1a9db67-7cb3-46f4-a603-d21e7eb17a8c" width="250"/></td>
    <td align="center"><b>Manage Settings</b><br><img src="https://github.com/user-attachments/assets/d07970eb-0ab8-4a88-a593-977f5f47d1d5" width="250"/></td>
  </tr>
</table>
