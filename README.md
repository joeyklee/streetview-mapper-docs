# Reference - Streetview Mapper 

> Streetview Mapper is a simple tool to allow curious mappers (like you!) to take «snapshots» of the world through Google Streetview. These snapshots are stored in a database to allow users to revisit what things they've found remarkable, noteworthy, strange, weird, and/or compelling. 

![ITP on Broadway](assets/img/main-image.png)

Hello! If you're here, you're probably looking to get started using the [Streetview Mapper](https://streetview-mapper.org). If so, you're in the right place!

## Signup

Before you can start using the [Streetview Mapper](https://streetview-mapper.org), you'll have to sign up with the following items:

| ✅ | Item | Description | Notes |
| :---- | --- | --- | --- |
| ☑️ | username | A username you want to be displayed publicly | required |
| ☑️ | email | An email address you will use to log-in publicly | required |
| ☑️ | password | A password that is at least 7 characters long.  | required |
| ☑️ | Google Maps API Key  | In order to use the Streetview Mapper, you'll need to make a Google Maps API Key with these features enabled 1) **Google Maps JavaScript API**, 2) **Places API**, and 3) **Street View Static API** | required |

⚠️ You will need to [Make a Google Maps API Key](#making-a-google-maps-api-key) before you can sign up. Please follow the instructions below 👇👇👇

## Making a Google Maps API Key

In order to make a Google Maps API Key for use with the Streetview Mapper you will need to create one. For the savy folks, you can probably figure out how to do this by reading [Google's instructions on how to get an API key](https://developers.google.com/maps/documentation/javascript/get-api-key), but for everyone else, I will step you through how to do this.

### Step-by-step

1. Make an google account and sign-in. 
2. Navigate to this link to the [Google Cloud Platform](https://console.cloud.google.com/google/maps-apis/). You'll have to agree to the terms of service and set your country.
   ![Landing Screen](assets/img/01__landing-screen.png)
3. Create a project. Let's call this: `streetview-mapper`
   ![Landing Screen](assets/img/02__create-project.png)
   ![Landing Screen](assets/img/03__name-project.png)
4. You'll end up on a screen with all these Google Maps features. So many things!
   ![Landing Screen](assets/img/04__google-maps-features.png)
5. Remember, we need to enable: 1) **Google Maps JavaScript API**, 2) **Places API**, and 3) **Street View Static API**. In order to do this, you can:
   1. Click on the square card with the API of interest then,
      ![Select Feature](assets/img/05__select-feature.png)
   2. Click **Enable** where prompted.
      ![Enable Feature](assets/img/06__enable-feature.png)
   3. Go back to the api list:
      ![Go back to list](assets/img/07__go-back-to-list.png)
      and select from the list
      ![Feature List](assets/img/08__feature-list.png)
   4. Repeat Steps 5.1 - 5.3 for the **Places API** 
      ![Feature List](assets/img/09__places-enable.png)
   5. Repeat Steps 5.1 - 5.3 for the **Street View Static API** 
      ![Feature List](assets/img/10__static-enable.png)
6. If you completed step 5 correctly, then you should see all those APIs enabled:
    ![Enabled APIs](assets/img/11__enabled-apis.png)
7. Use the sidebar dropdown (the 3 lines that look like a hamburger) to navigate to: > **APIs & Services** > **Credentials**
   ![Navigate to credentials](assets/img/12__navigate-to-credentials.png)
8. Create an API Key & then select **Restrict Key**
   ![Navigate to credentials](assets/img/13__create-key.png)
   Select **restrict key**: note that I've hidden my key
   ![Key displayed](assets/img/14__your-api-key.png)
9. **Scroll down** and restrict your API Keys by selecting them in the dropdown menu:
   * Select: Places API
     ![Restrict keys](assets/img/15__restrict.png)
   * Select:  Google Maps API
     ![Restrict keys](assets/img/16__restrict.png)
   * Select: Streetview API
     ![Restrict keys](assets/img/17__restrict.png)
   * Finally your keys will be restricted to those 3 APIs => **SAVE**
     ![Restrict keys](assets/img/18__restrict.png)
10. Now copy your API Key from your Google Cloud Console
    * **Copy your Key**
      ![Copy Key](assets/img/19__copy-key.png)
    * **Paste it** into the Signup page of Streetview Mapper
      ![Sign-up](assets/img/20__signup-screen.png)

## Privacy & Terms of Service

Dear Streetview Mapper,
My name is Joey Lee. I'm a [Adjunct Professor at New York University](https://tisch.nyu.edu/itp/itp-people/faculty/somethings-in-residence-sirs/joseph-lee) and a [Creative Technologist](https://jk-lee.com) based in Brooklyn, New York. I'm not a corporation or commercial entity trying to profit or make any money by providing this application and service. The Streetview Mapper DOES NOT USE ANY of your information whatsoever for anything besides allowing you to login to the application and create data as part of the service. Period. 

That being said, I do reserve the right to stop the service at any point without warning. I will try my best to keep Streetview Mapper alive as long as possible, but unfortunately I cannot make any guarantees. 

I'm glad you're interested to use the app!


## Supporting & Funding the Project

If you'd like to provide a few dollars to help with server costs and database hosting, I'd be psyched! This will help with the longevity of the project and also help ensure all your data collections can get a nice back up every once in a while. 

Feel free to reach out via email if you'd like to support the project: joeyklee@nyu.edu


