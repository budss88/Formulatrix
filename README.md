# Purpose 
A Repository manager is a library that can be used to store and retrieve JSON string or XML string. A unique string is used to indicate the item being stored.

# How to Run Test with FormulatrixUnitTest ( dotnet CLI )
Open your terminal on your Mac or Command Prompt Windows;

> git clone https://github.com/budss88/Formulatrix.git

> dotnet build Formulatrix.sln

> cd FormulatrixUnitTest

> dotnet test

# List Of xUnitTest

[Theory]

[InlineData("item1","{"to":"budhi.afrianto8@gmail.com","title":"Test OOP Formulatrix","body":"OOP Test Formulatrix"}",1)]

[InlineData("item2", "Budhi<title>Test OOP Formulatrix</title>OOP Test Formulatrix", 2)]

ReturnTrue_GivenParameters_RegisteringJSONXML

[Fact]

ReturnFalse_GivenDuplicatedItemNameAndItemType_RegisteringJSON

ReturnFalse_GivenDuplicatedItemNameAndItemType_RegisteringXML

ReturnFalse_GivenNoInputParameters_Registering

Return1_GivenitemName_getType

Return2_GivenitemName_getType

Return0_GivenitemNameWrong_getType

ReturnStringXML_GivenitemName_Retrieve

ReturnStringJson_GivenitemName_Retrieve

ReturnStringEmpty_GivenitemNameWrong_Retrieve

Deregister_GivenitemName
