# XamarinFormsTemplate

This is source code of newest Xamarin.Forms with .NET Standard Xamarin.Forms core project Template by Japan Xamarin User Group.

## Specification

- Xamarin.Forms 3.1.0.583944
- PackageReference (can use only Visual Studio 2017)
- .NET Standard 2.0 core project

# How to get

### Option 1: Clone the Repository (Recommended)

Clone the project on the following location directly:

```%USERPROFILE%\Documents\Visual Studio 2017\Templates\ProjectTemplates\Visual C#```

or make `Cross-Platform` directory in the above directory, then clone this repogitory.

From command prompt, you can install the template by the following commands:

```
cd "%USERPROFILE%\Documents\Visual Studio 2017\Templates\ProjectTemplates\Visual C#"
git clone https://github.com/ytabuchi/XamarinFormsTemplate.git
```

After the first installation, you can of course update your copy by ```git pull``` and you feel it's easier to update the templates than the other option.

### Option 2: Download the ZIP

- Download XamarinFormsTemplate-master.zip file from [GitHub](https://github.com/ytabuchi/XamarinFormsTemplate/archive/master.zip)
- Extract the zip file
- Move the extracted ```XamarinFormsTemplate-master``` folder to the following location:
```%USERPROFILE%\Documents\Visual Studio 2017\Templates\ProjectTemplates\Visual C#```


<img src="https://github.com/ytabuchi/XamarinFormsTemplate/blob/master/NewProject.png" alt="New project dialog" width="450" />

Please see [blog page (in Japanese)](http://ytabuchi.hatenablog.com/entry/vs-xf-template) for how to use.


# How to maintenance

`MyTemplate.vstemplate` located in Root folder is a Master file that is specify each child projects.
In each projects folder, there are `MyTemplate.vstemplate` files. They are the template setting files for each projects.

If Xamarin.Forms will be updated, you can just change the version numbers of each `MyTemplate.vstemplate` files

There are some macros such as `WizardExtension` in the template files. Please see [MSDN document](https://docs.microsoft.com/en-us/visualstudio/extensibility/visual-studio-template-schema-reference) for each meaning.
