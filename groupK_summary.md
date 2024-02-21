# Task 1: Explore the data and write a brief summary


## The cellular structure of the skin [2, 3]

The skin is divided into the epidermis, the dermis and the subcutis. The epidermis is the place of origin for skin lesions. The deepest layer of the epidermis, the stratum basale, houses the basal cells – stem cells of the skin – and melanocytes, cells that produce the skin’s pigment called melanin. The more superficial layers contain stratified squamous epithelial cells that become increasingly keratinized as they get closer to the surface of the skin.



## Skin lesions, etiology and relations [4]
The dataset contains six types of lesions or tumors. Tumors of the skin can be divided into benign and premalignant skin lesions, and malignant epidermal tumors. In the first category we find seborrheic keratosis (SEK), a skin lesion mostly found in middle-aged or older individuals. They are round, coinlike plaques that vary in diameter and have a “stuck-on” appearance. They are occasionally removed due to visual similarities with melanoma. They are also characteristically keratinized, with keratin-filled cysts on the surface.

Also in the first category are actinic keratoses (ACK), premalignant lesions caused by UV-induced DNA-damage. They are most common in fair-skinned individuals. They feature hyper-keratinization, meaning an excessive hardening of the skin, and they may progress to squamous cell carcinoma, although only 0.1-2.6% of cases do this per year – most regress or remain stable, but are often treated for cosmetic or preventative reasons. They are usually less than 1 cm in diameter, tan-brown or red, and rough to the touch.

The malignant epithelial tumors include basal cell carcinoma, squamous cell carcinoma and melanoma. One thing they all have in common is an origin in UV-induced DNA-damage resulting in unchecked cell division and growth. Melanoma originates from melanocytes, basal cell carcinoma originates from the skin stem cells, and squamous cell carcinoma originates from the skin cells (stratified squamous epithelial cells) in the superficial layers of the epidermis.

Basal cell carcinomas (BCC) appear as pearly papules, often feature prominent, dilated subdermal blood vessels, and some may contain melanin and thus look like melanomas or nevi.

Squamous cell carcinoma (SCC) is more common in older individuals, and more often men than women. They appear as sharply defined red, scaly plaques. More advanced cases may bleed and look nodular. They rarely metastasize and only after a very long time.

Melanomas (MEL) are somewhat related to nevi. Nevi (NEV) are benign growths of melanocytes existing at birth and may vary in appearance either having a mostly smooth, tan-to-brown surface or a raised appearance with variable pigmentation and slightly irregular borders. These can, but are unlikely to, develop into melanomas. Unlike nevi, melanomas often exhibit striking variations in pigmentation, including shades of black, brown, red, dark blue and gray. The borders are irregular and often “notched”. Unlike the other malignant lesions, melanoma is highly invasive and regularly metastasizes.



## An exploration of our data: Image contents and data summary [1]
The data set includes some images of low quality. This means that some of the images either were not included or were segmented in a non-accurate way. An example of a picture of too low quality is PAT_782_1494_418. This is a picture of the top of a head but because the lesion is spread out and not centered around one place the bad image quality makes it impossible to annotate the area precisely. 

The CSV file contains information about the patients in the images. For all patients there is available data categorized in the columns; patient id, lesion id, age, region, diagnostic, itch, grew, hurt, changed, bleed, elevation, img id and biopsied. Moreover, the meta data includes personal information such as the background of the patient's parents, cancer history, and habits regarding drinking and smoking. This does not apply for all patients since additional data is missing for around 35 pct. (804) of patients. 

Looking further into the data we see that there is a wide age range amongst the patients reaching from 6 to 94 years old, which is a positive because it makes the data more representative. Of the 1494 patients that have further information provided about them 52.1% (779 people) of them have a history of cancer and 45.6% (681 people) have a history of skin cancer.  



## SOURCES

[1] Pacheco et al. (2020). PAD-UFES-20: A skin lesion dataset composed of patient data and
	clinical images collected from smartphones. Data Brief. vol. 32.

[2] Hole, John W (2014). Hole’s Essentials of Human Anatomy and Physiology, 12th ed.

[3] Kolarsick et al. (2011). Anatomy and Physiology of the Skin. Journal of the Dermatology
	Nurses’ Association, July-August 2011, Vol. 3, issue 4. 

[4] Abbas et al. (2018). Robbins’ Basic Pathology, 10th ed.

