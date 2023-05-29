<div align="center">
  <a href="https://www.learnitive.com/">
    <img src="favicon-social-transparent.png" alt="Logo" height="100">
  </a>

  <br />
  <h3 align="center">Learnitive + MS Word 🚀</h3>

  <p align="center">
    Enhance your writing experience with Learnitive + MSWord, a Microsoft Office macro that brings Learnitive AI directly into Word.
    <br />
    <a href="https://www.learnitive.com/ai-api"><strong>Explore the Learnitive API »</strong></a>
    <br />
      <a href="https://www.learnitive.com/">
    <img src="msword-demo-video.gif" alt="Learnitive-video" height="100">
  </a>
    <br />
    <a href="https://github.com/learnitive/MSWord/issues">Report Bug</a>
    ·
    <a href="https://github.com/learnitive/MSWord/issues">Request Feature</a>
  </p>


</div>


## Usage

This is a simple Microsoft Word Macro allowing you to use AI prompts within Word through the Learnitive API. These instructions may only apply to recent versions of Microsoft Windows. 

1. Open **Microsoft Word** `>` **View** `>` **Macros** (or `Alt-F8`).
2. Enter a name (should be **"Learnitive"** or you will need to change the macro code).
3. The editor will open up, replace everything with the code in the `macro.vba` file.
4. Replace `YOUR-KEY-HERE` with your own Learnitive API key. Get your key from the [https://www.learnitive.com/ai-api](https://www.learnitive.com/ai-api)
5. Run the `Learnitive` subroutine by pressing `Alt-F8` and clicking **Run**. 
6. Enter the `input prompt` you want to send to the **Learnitive API** in the input box that appears.
7. Response from the Learnitive API will be inserted into the document where the cursor was last placed.

## Troubleshooting

If you receive an error related to `WinHttp.WinHttpRequest.5.1`, it means that the `WinHttp` library is not registered on your computer. To resolve this issue, you can try re-registering the library by running the following command in an elevated command prompt:

```
regsvr32 %systemroot%\system32\winhttp.dll
```

If the error persists, you may need to reinstall the library. You can download it from the Microsoft website.

## Disclaimer
The authors and contributors of this program provide it as-is, without any warranties or guarantees. They cannot be held responsible for any damages resulting from the use of this program.

## License
This program is licensed under the MIT license.

## Original Author
Johann Dowa

## Modification
Updated by: Learnitive
