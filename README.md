# olapohaku
Website for Kuzari designed by Emma Champ for StartSimple Sites, 2025.

This is your site editing guide.



As this is a single-page site, your homepage contains everything.  If you are adding pages in future, be sure to add some navigation links!

    Your webpage consists of:
            
        - Header section containing the logo (logo.png) and title.
        - Hero section with an image (hero.jpg) and a "Shop" link linking to your Shopify storefront
        - Gallery showcasing three images (collection1.jpg collection2.jpg and collecton3.jpg) all of which link to the corresponding collection on Shopify.
        - About section containing a paragraph about the business and the owner
        - FAQ section with collapsible answers
        - Contact section with customer service email/phone number and any social media links you may wish to share
            
    Editing the Logo Image:

        1) Navigate to the Assets folder
        2) Save the desired logo image to this folder.
        3) Name the image "logo.png" and replace the previous file of this name
        4) If your image format is not png, you will need to edit olapohaku.html to reflect this:
            - Open olapohaku.html in any text editor and replace all instances of "logo.png" with "logo.jpg" or whatever file type you are using instead
            - Be sure not to remove the path - that is "Assets/" preceding the logo image filename
            - This process will be the same for any images you replace.  If you attempt to replace any image and find that it disappears, it's worth checking that the file extension of the image matches what's in the html.

    Editing the Title:

    1) Text of title
        - Open olapohaku.html
        - Navigate to the <head> section
        - Replace the text between the <title> tags with your choice of heading.  At time of handover the title reads "Ola Pōhaku"
        
    2) Font of title
        - Open style.css
        - At the very top you will see the imported fonts 
            # If your font is freely available, you can change this to reflect where you are importing your font from
            # If you are using a proprietary font that you have downloaded, you should instead replace the imported font 
        - Once the font is correctly imported or its path has been established, navigate to the block of style.css which pertains to header h1
        - Replace font-family 'font name' with the new font name.

    Replacing the Hero Image:
        1) Navigate to the Assets folder
        2) Save the desired hero image to this folder
        3) Name the image "hero.jpg" and replace the previous "hero.jpg"
        
    Editing the Gallery:
    
    Editing the "About" Paragraph:
    
        - Open olapohaku.html
        - Simply navigate to the "About" section and replace the existing paragraph text with your desired copy
   
    Editing the FAQ:

        - to add a new item to the FAQ, paste the following template block into the FAQ section and fill out the details as labelled:

<div class="faq-item">
      <details>
        <summary>This is where you write the question?</summary>
        <p>This is where you write the answer to the question.</p>
      </details>
    </div>
    
        - to delete an item from the FAQ simply delete the block pertaining to it between <div class="faq-item"> and </div>
