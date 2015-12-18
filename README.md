# Telephone directory Mobile Edition
You are to build a mobile application that provides a telephone directory.

## Entries
The application handles a set of entries, that contain a first name, last name, and a telephone number.

The entries should be validated, so that it's not possible to enter an empty first or last name; and the phone number should be of the form
```
+39 02 1234567
```

That is a "+" followed by a nonempty group of digits, a space, a nonempty group of digits, a space, a group of digits with at least 6 digits.

The application consists of the following pages:
* **Home page**
  * Contains a text field that allows to search through all the entries by name or number. When I enter text in the field, the page will be reloaded with a table containing all the entries that match the text I entered.
  * The page contains a link to the "add new entry" page.
  * When an entry is displayed, it contains a link to the "edit this entry" page.
* **Add new entry page**
  * Contains a form for entering a new entry.
  * Contains an "import from contacts" button to import a single contact from the existing contacts list of the smartphone
* **Edit entry page**
  * Contains a form for modifying an existing entry.

### Extra activities (not mandatory)
* Deploy the application in a Mobile App Distribution Platform (e.g. TestFlight, HockeyApp, Beta (Fabric), etc.)
* Compatibility with Tablet devices
* Screen rotation handling


## General requirements
- You may use **iOS** or **Android** platform and whatever programming language you prefer. Use something that you know well.
- You should commit your code on **GitHub** or any other SCM repository you prefer (e.g. bitbucket, gitlab, etc) and send us the link.
- You should release your work with an OSI-approved open-source **license** of your choice.
- You should deliver the sources of your application, with __a README__ that explains how to compile and run it.

**IMPORTANT:**  Implement the requirements focusing on **writing the best code** you can produce.
