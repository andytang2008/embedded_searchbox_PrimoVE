# embedded_searchbox_PrimoVE
The embedded search box for Primo VE

An embedded search box was created for Primo VE  which could search for fields, such as Title, Author, Subject, ISBN, ISSN, and Call number. We modified the search box code  coming from “Creating a Search Box With Deep Links to the New UI” in the link “https://knowledge.exlibrisgroup.com/Primo/Product_Documentation/New_Primo_User_Interface/New_UI_Customization_-_Best_Practices#Creating_a_Search_Box_With_Deep_Links_to_the_New_UI”, and fulfill our target.

It is a good search box you could put into LibGuides pages if you added the corresponding search scope. The default search scope is EVERYTHING.

The interface will be like below.

![Picture1](https://user-images.githubusercontent.com/20071142/201226915-bff73b94-c812-4a5a-b46e-d72d4559d46f.png)


Intending to use the search box in your library environement, you have to make  some changes and customizations as follows.

![Picture2](https://user-images.githubusercontent.com/20071142/201227129-d43d92a2-f80e-43ea-94a0-a7067dfd857e.png)
![picture3](https://user-images.githubusercontent.com/20071142/201227135-eb2655a7-92db-43a6-a19c-7bfa2372bb1a.png)



It uses Javascript code to get the select box value and replace the “any,contains,keyword” parameter with “title,contains,keyword”, or “creator, contains, keyword” etc, so that this embedded search box could search for title, author, subject, ISBN, ISSN, and call number in Primo VE.

The code is in  https://github.com/andytang2008/embedded_searchbox_PrimoVE
