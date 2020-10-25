# Allergen Spotter

## Inspiration

Having Celiac from a young age and always having to read labels to check if I can eat something, also having a hard time whenever others tried to find something for me to eat. The goal was to create something that would make this easier for all.

## What it does

Once a user has snapped a picture of a label, our Optical Character Recognition (OCR) software can distinguish key ingredients that pertain to the user's allergies. In a database, we've compiled all the main ingredients and have associated their allergens. Hence, even if an allergy is super rare, AllergenSpotter has it on file, as well as all of its variants and products that resemble it. 
After having determined whether the user can safely consume this product, the information will be displayed to the user. Furthermore, AllergenSpotter stores the scanned items and products for future reference. 
Additionally, the user can keep important phone numbers on AllergenSpotter, such as that of an allergist or emergency contact person, in the case of an allergic reaction. 

## How we built it

We came up with a design on Canva, then created an demo site with Wix. Although they don't work yet, we wanted to display how our app would look like. Then we started looking into OCR programs with Python. Towards the end, we were thinking about implementing a Cloud Vision API.

## Challenges we ran into

The first program we created with Tesseract didn't work well. It had trouble recognizing the words and only found syllables here and there. That's why we transitioned to the Cloud Vision API.

## Accomplishments that we're proud of

We got the mock-up done and we believe that done > perfect. There's a lot of room for improvement as far as building the website and app goes, but that'll take time. We still have to learn a lot.

## What we learned

We learned to start earlier and how to create simple web apps.

## What's next for AllergenSpotter

Being able to actually detect text, adding more option for allergens and options to include severity or importance of staying away from a certain food item (preference or allergy). In the future this could also be used for various products, such as hand creams, medicine and cosmetics. Our goal is to help individuals and promote transparency and clarity in labels.
