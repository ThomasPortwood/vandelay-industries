Hello Vandelay Industries! 

My name is Tom and I'll be your engineering point-of-contact here at Terazo. We're excited to be working with you! 

I've been asked to provide feedback on the first draft of your REST application programming interface to get us started.

First off, congratulations on the first draft. Vandelay has made a few key decisions that will set it apart from competitors: strictly adhering to the battle-tested and widely adopted REST philosophy, and using a formal standard for the documentation. These decisions will drive adoption of the API because of clear documentation, minimize development costs and time because of powerful tooling, and help maintain agility in the future as the business grows and adapts.

I've made a temporary [git repository](https://github.com/ThomasPortwood/vandelay-industries) so I can collaborate with the Vandelay engineers. I've included a detailed explanation of each proposed change in a [GitHub issue](https://github.com/ThomasPortwood/vandelay-industries/issues?q=is%3Aissue+is%3Aclosed), made the proposed change, and then cataloged the changes in a [changelog](https://github.com/ThomasPortwood/vandelay-industries/blob/master/CHANGELOG.md) using a [super useful widely adopted format](https://keepachangelog.com/en/1.0.0/). In the future, we'll have discussion on GitHub issues before permitting proposed changes to be merged. 

I've structured my feedback in order of priority:
- Adherence to the principles of REST
- Usability and documentation quality
- Further recommendations

- Adherence to the principles of REST
    - [PATCH verb should be replaced with PUT verb and refer to a specific resource](https://github.com/ThomasPortwood/vandelay-industries/issues/6)
    - [PUT response should clarify whether resource was created or updated](https://github.com/ThomasPortwood/vandelay-industries/issues/18)
    - [POST response should contain only the newly created resource](https://github.com/ThomasPortwood/vandelay-industries/issues/4)
    - [DELETE verb should be used for Removal of item from collection](https://github.com/ThomasPortwood/vandelay-industries/issues/5)

- Usability and documentation quality
    - [Resource name Inventory used in plural and singular references](https://github.com/ThomasPortwood/vandelay-industries/issues/3)
    - [Missing security definitions section](https://github.com/ThomasPortwood/vandelay-industries/issues/14)
    - [Missing contact in info object](https://github.com/ThomasPortwood/vandelay-industries/issues/12)
    - [Missing tag descriptions](https://github.com/ThomasPortwood/vandelay-industries/issues/17)

- Further recommendations
    - [Remove support for insecure http protocol](https://github.com/ThomasPortwood/vandelay-industries/issues/20)
    - [Unused 'null' and indentation mistake](https://github.com/ThomasPortwood/vandelay-industries/issues/2)
    - Update to the OpenAPI specification 3.0 (formerly Swagger specification)