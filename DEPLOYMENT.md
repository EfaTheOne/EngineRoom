# How to Launch "The Engine Room" for Free

Since your project is built with standard web technologies (HTML, CSS, JavaScript), you can host it for free on high-performance platforms like **Netlify** or **Vercel**. You do not need a paid server.

## Option 1: Netlify Drop (Easiest)
**Best for:** Getting a link in 30 seconds.

1.  Open [Netlify Drop](https://app.netlify.com/drop).
2.  Open your File Explorer to `Documents`.
3.  Drag and drop your entire **`TheEngineRoom`** folder onto the Netlify page.
4.  Wait a few seconds. Netlify will give you a live URL (e.g., `https://romantic-tesla-12345.netlify.app`).
5.  **Done!** You can share this link.

## Option 2: GitHub + Vercel (Professional)
**Best for:** Long-term projects where you want to save your code history.

1.  **Create a GitHub Account** at [github.com](https://github.com).
2.  **Upload your code**:
    *   Create a new repository named `engine-room`.
    *   Upload all your files to it.
3.  **Deploy on Vercel**:
    *   Go to [vercel.com](https://vercel.com) and sign up with GitHub.
    *   Click "Add New..." -> "Project".
    *   Select your `engine-room` repository.
    *   Click "Deploy".
4.  **Done!** Vercel gives you a secure `https` link and automatically updates the site whenever you push code changes to GitHub.

## Important Note on API Keys
Your Google Gemini API Key is stored in your **browser's local storage**. 
*   When you share the link, other users will NOT see your key.
*   They will see the "Simulation Mode" until they enter their own key in the Settings menu.
*   **This is a good thing!** It prevents your personal key from being stolen or overused.

## Troubleshooting
*   **Images missing?** Ensure all image files are inside the folder you dragged.
*   **Links broken?** Make sure you are using relative links (e.g., `dashboard.html` instead of `C:/Users/...`). (We have already verified this!).
