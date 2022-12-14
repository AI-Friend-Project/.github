# AI Friend 
---
### What is AI Friend?
An application that identifies users' interests while talking to chatbots and matches people with similar interests.

> AI-Friend can
>> be a good friend for people who lonely and have difficulty in relationships.
>> help users easily make new relationships with analysis and expansion.


# System Architecture
<img width="855" alt="image" src="https://user-images.githubusercontent.com/65584699/207514631-0d3b7497-d245-4488-9daf-0ba4ac0ce884.png">

# Key Features
Detailed features and screens are described later.
- Chat with AI
<img width="544" alt="image" src="https://user-images.githubusercontent.com/65584699/207515482-cd0a6a60-05bf-4111-b4a9-406f2c3b5626.png">

- Identify and recommend interests
<img width="317" alt="image" src="https://user-images.githubusercontent.com/65584699/207515865-80195b02-4503-4101-abd7-556f33781532.png">


# Used AI Model
We used **AIHub**'s topic-specific text-daily conversation data set.
- link : <https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=543/>
## GPT-2
![ezgif com-gif-maker](https://user-images.githubusercontent.com/65584699/207517716-49d0bfd7-9422-46c7-afff-246298a9cb5a.gif)

## KeyBERT, Word2Vec
#### - KeyBERT
Extract keywords from users' chat content

#### - Word2Vec
Calculate word similarity between keywords and categories, Connect one category with the highest similarity to the user



## Requirements
| Field | |
|----------|:-------------:|
|__Client__| <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=Kotlin&logoColor=black"> <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=Android&logoColor=black"> <img src="https://img.shields.io/badge/Android Studio-3DDC84?style=for-the-badge&logo=Android Studio&logoColor=black">|
|__Backend & Server__| <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"> |
|__DB__| <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=Firebase&logoColor=black"> |
|__AI__| GPT-2, KeyBERT, Word2Vec|
|__Others__| <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=black"> |

| library | version |
| ------ | ------ |
| python | 3.10.9 |
| kotlin | |
| GPT-2 |  |
| KeyBERT |  |
| Word2Vector | |

### Members - _TEAM 4_
| Name | Field |
| ------ | ------ |
| 곽민선 | |
| 이가현 | Client, Word2Vec | 
| 이예준 | Backend & Server, GPT-2|
| 이지윤 | Client, KeyBERT |





 
