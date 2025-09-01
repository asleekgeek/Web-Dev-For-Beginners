<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "537f02a36d73db093cbb8b9b44867645",
  "translation_date": "2025-09-01T15:47:07+00:00",
  "source_file": "9-chat-project/solution/backend/python/README.md",
  "language_code": "ne"
}
-->
# कोड चलाउनुहोस्

## सेट अप

भर्चुअल वातावरण बनाउनुहोस्

```sh
python -m venv venv
source ./venv/bin/activate
```

## निर्भरता स्थापना गर्नुहोस्

```sh
pip install openai flask flask-cors 
```

## एपीआई चलाउनुहोस्

```sh
python api.py
```

## फ्रन्टएन्ड चलाउनुहोस्

पक्का गर्नुहोस् कि तपाईं फ्रन्टएन्ड फोल्डरमा हुनुहुन्छ

*app.js* फाइल खोज्नुहोस्, `BASE_URL` लाई तपाईंको ब्याकएन्ड URL मा परिवर्तन गर्नुहोस्

यसलाई चलाउनुहोस्

```
npx http-server -p 8000
```

च्याटमा सन्देश टाइप गर्न प्रयास गर्नुहोस्, तपाईंले प्रतिक्रिया देख्नुहुनेछ (यदि तपाईंले यो Codespace मा चलाउनु भएको छ वा पहुँच टोकन सेट अप गर्नुभएको छ भने)।

## पहुँच टोकन सेट अप गर्नुहोस् (यदि तपाईंले यो Codespace मा चलाउनुहुन्न भने)

[Set up PAT](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens) हेर्नुहोस्

---

**अस्वीकरण**:  
यो दस्तावेज़ AI अनुवाद सेवा [Co-op Translator](https://github.com/Azure/co-op-translator) प्रयोग गरेर अनुवाद गरिएको हो। हामी शुद्धताको लागि प्रयास गर्छौं, तर कृपया ध्यान दिनुहोस् कि स्वचालित अनुवादमा त्रुटिहरू वा अशुद्धताहरू हुन सक्छ। यसको मूल भाषा मा रहेको मूल दस्तावेज़लाई आधिकारिक स्रोत मानिनुपर्छ। महत्वपूर्ण जानकारीको लागि, व्यावसायिक मानव अनुवाद सिफारिस गरिन्छ। यस अनुवादको प्रयोगबाट उत्पन्न हुने कुनै पनि गलतफहमी वा गलत व्याख्याको लागि हामी जिम्मेवार हुने छैनौं।