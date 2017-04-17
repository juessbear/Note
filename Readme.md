# AIA Test Case
* **TestCase1 (VHR had been compled)**
    * **AC1** : `First login + finished VHR --> S3.1 Fitness Target`
* **TestCase2 (VHR process)** (Multiple language)
    * **AC2** : `First login + never finished VHR --> VHR Survey Tutorial`
    * **AC3** : `Check items in S2.1`
    * **AC4** : `Tap button['Get my vitality age'] to S2.2` ==Check items part the same as AC3?==
    * **AC5** : `Tap button['Get my vitality age'] to S2.2` ==The same as AC4？==
    * **AC8** : `Check items in S2.2`
    * **AC9** : `Check items in S2.2` ==The same as AC8？==
    * **AC10** : `Check default value in S2.2` ==The same image capture as AC8？==
    * **AC11** : `Check default value in S2.2` ==The same as AC10？==
    * **AC12** : <br/>
        `1. Change values in S2.2`<br/>
        `2. Tap Back button back to S2.1`<br/>
        `3. Go to S2.2 check whether the values as Step1 inputed`<br/>
    * **AC14** : `Tap back button in S2.2 then go back to S2.1` ==Included in AC12==
    * **AC15** : <br/>
        `1. Tap indicator 2 to page2(S2.3)`<br/>
        `2. Tap indicator 3 to page3`<br/>
        `3. Tap indicator 4 to page4`<br/>
        `4. Tap indicator 5 to page5`<br/>
        `5. Tap indicator 6 to page6`<br/>
    * **AC16** : `Open picker` ==Included in AC12==
    * **AC17** : `Tap indicator 2 to page2(S2.3)`==Included in AC15==
    * **AC19** : `Check default value in S2.2` ==The same as AC10？==
    * **AC20** : `Check picker option range` ==Included in AC12==
    * **AC21** : `Open picker and drag up and down to select the option` ==Included in AC12==
    * **AC22** : `Open picker and drag up and down to select the option` ==Included in AC12==
    * **AC23** : `Tap the button['Next'] and go to S2.3 in S2.2`
    * **AC24** : `Check picker option range` ==The same as AC20？==
    * **AC26** : <br/>
        `* Tap the button['Next'] and go to S2.3 in S2.2` ==Included in AC15==<br/>
        `* Tap indicator 2 to page2(S2.3) in page1(S2.2)` ==Included in AC24==<br/>
    * **AC27** : `Check items in page2`
    * **AC28** : `Check items in page2` ==The same as AC27？==
    * **AC29** : `Check items in page2` ==The same image capture as AC27？==
    * **AC30** : `Check default in page2`
    * **AC31** : `Check options of question "How many days per week do you exercise?" in page2` ==Cap 5 image?==
    * **AC32** : `Check options of question "How intense are your exercise session" in page2` ==Cap 3 image?==
    * **AC33** : `Check options of question "How intense are your exercise session" in page2` ==The same as AC32?==
    * **AC34** : `Selected options of question "How intense are your exercise session" in page2 should be highlight` ==Included in AC32?==
    * **AC37** : `Tap back button in page2 then go to page1`
    * **AC38** : <br/>
        `1. Tap indicator 1 to page1`<br/>
        `2. Tap indicator 3 to page3`<br/>
        `3. Tap indicator 4 to page4`<br/>
        `4. Tap indicator 5 to page5`<br/>
        `5. Tap indicator 6 to page6`<br/>
    * **AC39** : `Tap next button in page2 then go to page3`
    * **AC41** : `Check items in page3`
    * **AC42** : `Check items in page3` ==The same as AC41?==
    * **AC43** : `Check items in page3` ==The same image capture as AC41?==
    * **AC44** : `Check default values in page3`
    * **AC45** : `Check values of each option in page3` ==Cap 16 images?==
    * **AC46** : `Check values of each option in page3` ==The same as AC45?==
    * **AC47** : `Selected options should be highlight` ==Included in AC45==
    * **AC48** : <br/>
        `1. Change values in page3`<br/>
        `2. Tap Back button back to page2`<br/>
        `3. Go to page3 check whether the values as step1 inputed`<br/>
    * **AC49** : `Tap back button in page3 then go to page2` ==Included in AC48==
    * **AC50** : <br/>
        `1. Tap indicator 1 to page1`<br/>
        `2. Tap indicator 2 to page2`<br/>
        `3. Tap indicator 4 to page4`<br/>
        `4. Tap indicator 5 to page5`<br/>
        `5. Tap indicator 6 to page6`<br/>
    * **AC53** : `Tap the customer button in page3 then go to step3 customized value page(S2.4.1)`
    * **AC54** : `Tap the next button in page3 then go to page4`
    * **AC55** : `Check items in step3 customized value page`
    * **AC56** : `Check items in step3 customized value page` ==The same as AC55==
    * **AC57** : `Open picker of Blood Pressure`
    * **AC58** : `Check the range of values in the picker of Blood Pressure`
    * **AC59** : `Check the range of values in the picker of Blood Pressure` ==The same as AC58==
    * **AC60** : `Selected one option and close the picker of Blood Pressure then check the value correct or not`
    * **AC61** : `Open picker of Glucose and check the range of values`
    * **AC62** : `The options of the picker of Glucose should be changed relatively`
    * **AC63** : `Select an option from picker of Glucose and check whether the value changed`
    * **AC64** : `Open picker of Cholesterol and check the range of values`
    * **AC65** : `The options of the picker of Cholesterol should be changed relatively`
    * **AC66** : `Select an option from picker of Cholesterol and check whether the value changed`
    * **AC67** : <br/>
        `1. Tap Cancel button in step3 customized value page`<br/>
        `2. Prompted with message "Are you sure you would like to discard the changes?"`<br/>
        `3. Tap Cancel button in the alert dialog`<br/>
        `4. Stay in step3 customized value page`<br/>
    * **AC68** : `Tap Save button in step3 customized value page then go to page3` ==Included in AC69==
    * **AC69** : `Tap Save button in step3 customized value page then go to page3 and check the value`
    * **AC70** : `Tap Save button in step3 customized value page then go to page3 and the page3 should be no highlight` ==The same image capture as AC69==
* **TestCase3 (Skip VHR in Tutorial)**
    * **AC2** : `First login + never finished VHR --> VHR Survey Tutorial`
    * **AC6** : `Tap button['I ll do it later'] to S2.8`
* **TestCase4 (Skip VHR in Step 1)**
    * **AC2** : `First login + never finished VHR --> VHR Survey Tutorial`
    * **AC4** : `Tap button['Get my vitality age'] to S2.2`
    * **AC18** : <br/>
        `1. Tap button['Skip VHR'] to S2.8`<br/>
        `2. Prompt alert`<br/>
        `3. Tap button['OK'] to S2.8`<br/>
    * **AC13** : `Tap button['Skip VHR'] to S2.8`==Included in AC18==
* **TestCase5 (Skip VHR in Step 2)**
    * **AC2** : `First login + never finished VHR --> VHR Survey Tutorial`
    * **AC4** : `Tap button['Get my vitality age'] to S2.2`
    * **AC23** : `Tap the button['Next'] and go to S2.3 in S2.2`
    * **AC35** : `Tap button['Skip VHR'] in S2.3 then go to S2.8`
* **TestCase6 (Skip VHR in Step 3)**
    * **AC2** : `First login + never finished VHR --> VHR Survey Tutorial`
    * **AC4** : `Tap button['Get my vitality age'] to S2.2`
    * **AC23** : `Tap the button['Next'] and go to S2.3 in S2.2`
    * **AC39** : `Tap next button in page2 then go to page3`
    * **AC51** : `Tap button['Skip VHR'] in page3 then go to S2.8`
* **No network case** ==Can't control network==
    * **AC7**
    * **AC18 (VHR-15)** 
    * **AC25**
    * **AC40**
    * **AC52**


