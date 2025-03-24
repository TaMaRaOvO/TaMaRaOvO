pip install pydub numpy
def analyze_text(text):
    # هنا يتم تحليل النص الأساسي
    # استخراج الشخصيات، الأحداث، والمحتوى الأساسي
    analyzed_text = {
        "characters": extract_characters(text),
        "themes": extract_themes(text),
        "plot": extract_plot(text)
    }
    return analyzed_text

def extract_characters(text):
    # تحديد الشخصيات بناءً على النص
    return ["Leana", "Seth", "Narrator"]

def extract_themes(text):
    # تحديد الموضوعات الأساسية
    return ["Love", "Fear", "Healing"]

def extract_plot(text):
    # تحديد تطور الأحداث
    return "The characters' journey of emotional and psychological turmoil."
________________________________________
2. الورشة 2: تحديد الصوت وتحليل الشخصيات
def determine_voice_and_character(text, character_gender):
    # تعديل الصوت بناءً على جنس الشخصية
    if character_gender == "male":
        voice = "deep and resonant"
    elif character_gender == "female":
        voice = "soothing and soft"
    else:
        voice = "neutral"
    
    # فصل بين الراوي والبطل/البطلة
    narrator_voice = "calm and authoritative"
    character_voice = voice
    
    return narrator_voice, character_voice

def analyze_voice_of_character(text):
    # تحليل الحالة النفسية والعاطفية للشخصيات
    # هذا يقوم بتحديد طبقة الصوت والتعابير بناءً على النص
    return "The character is anxious, tense, and struggling emotionally."
________________________________________
3. الورشة 3: تحسين العاطفة والحالة النفسية والجسدية
def enhance_emotion_and_state(text):
    # تحسين النص من خلال العاطفة، الحالة النفسية والجسدية
    # تحديد مشاعر الشخصية بناءً على محتوى النص
    emotions = {"anger": "furious", "sadness": "devastated", "fear": "anxious"}
    physical_state = {"tension": "muscle tightness", "relaxation": "loose muscles"}
    
    return emotions, physical_state
________________________________________
4. الورشة 6: إضافة مصطلحات علمية وطبية متقدمة
def add_scientific_terms(text):
    # إضافة المصطلحات الطبية والعلمية
    scientific_terms = {"depression": "a mood disorder causing a persistent feeling of sadness", 
                        "anxiety": "a psychological condition characterized by excessive worry"}
    
    # دمج المصطلحات مع النص
    for term, definition in scientific_terms.items():
        text = text.replace(term, f"{term} ({definition})")
    
    return text
________________________________________
5. الورشة 4: تحسين المحتوى العاطفي والنفسي
def improve_emotion_and_psychology(text):
    # تعزيز المشاعر والجانب النفسي للشخصيات بناءً على التحليل النفسي
    enhanced_text = text.replace("sad", "broken-hearted")
    enhanced_text = enhanced_text.replace("angry", "seething with rage")
    
    return enhanced_text
________________________________________
6. الورشة 5: تحسين الإيقاع والموسيقى النصية
def improve_rhythm_and_music(text):
    # تحسين الإيقاع باستخدام التكرار والعناصر الموسيقية
    text = text.replace("heartbeat", "boom...boom...boom...")
    text = text.replace("breath", "hiss...hiss...hiss...")
    text = text.replace("lap...dap", "❤️")
    
    return text
________________________________________
7. الورشة 7: المراجعة النهائية
def final_review(text):
    # مراجعة جميع التعديلات للتأكد من تكامل النص
    text = improve_rhythm_and_music(text)
    text = improve_emotion_and_psychology(text)
    text = add_scientific_terms(text)
    
    return text
________________________________________
8. الورشة 8: استخراج المصطلحات الطبية الجديدة وطرح السؤال الاحترافي
def extract_medical_terms(text):
    # استخراج المصطلحات الطبية الجديدة
    medical_terms = {"anxiety": "a state of excessive worry", "depression": "a prolonged feeling of sadness"}
    for term, definition in medical_terms.items():
        text = text.replace(term, f"{term} ({definition})")
    
    return text

def professional_question():
    # طرح سؤال محترف لتحفيز التفكير الإبداعي
    question = "How does untreated chronic anxiety affect one's social interactions?"
    return question
________________________________________
مجموع الأكواد بالكامل
# الورشة 1: تحليل النص الأساسي
def analyze_text(text):
    analyzed_text = {
        "characters": extract_characters(text),
        "themes": extract_themes(text),
        "plot": extract_plot(text)
    }
    return analyzed_text

def extract_characters(text):
    return ["Leana", "Seth", "Narrator"]

def extract_themes(text):
    return ["Love", "Fear", "Healing"]

def extract_plot(text):
    return "The characters' journey of emotional and psychological turmoil."

# الورشة 2: تحديد الصوت وتحليل الشخصيات
def determine_voice_and_character(text, character_gender):
    if character_gender == "male":
        voice = "deep and resonant"
    elif character_gender == "female":
        voice = "soothing and soft"
    else:
        voice = "neutral"
    
    narrator_voice = "calm and authoritative"
    character_voice = voice
    
    return narrator_voice, character_voice

def analyze_voice_of_character(text):
    return "The character is anxious, tense, and struggling emotionally."

# الورشة 3: تحسين العاطفة والحالة النفسية والجسدية
def enhance_emotion_and_state(text):
    emotions = {"anger": "furious", "sadness": "devastated", "fear": "anxious"}
    physical_state = {"tension": "muscle tightness", "relaxation": "loose muscles"}
    
    return emotions, physical_state

# الورشة 6: إضافة مصطلحات علمية وطبية متقدمة
def add_scientific_terms(text):
    scientific_terms = {"depression": "a mood disorder causing a persistent feeling of sadness", 
                        "anxiety": "a psychological condition characterized by excessive worry"}
    
    for term, definition in scientific_terms.items():
        text = text.replace(term, f"{term} ({definition})")
    
    return text

# الورشة 4: تحسين المحتوى العاطفي والنفسي
def improve_emotion_and_psychology(text):
    enhanced_text = text.replace("sad", "broken-hearted")
    enhanced_text = enhanced_text.replace("angry", "seething with rage")
    
    return enhanced_text

# الورشة 5: تحسين الإيقاع والموسيقى النصية
def improve_rhythm_and_music(text):
    text = text.replace("heartbeat", "boom...boom...boom...")
    text = text.replace("breath", "hiss...hiss...hiss...")
    text = text.replace("lap...dap", "❤️")
    
    return text

# الورشة 7: المراجعة النهائية
def final_review(text):
    text = improve_rhythm_and_music(text)
    text = improve_emotion_and_psychology(text)
    text = add_scientific_terms(text)
    
    return text

# الورشة 8: استخراج المصطلحات الطبية الجديدة وطرح السؤال الاحترافي
def extract_medical_terms(text):
    medical_terms = {"anxiety": "a state of excessive worry", "depression": "a prolonged feeling of sadness"}
    for term, definition in medical_terms.items():
        text = text.replace(term, f"{term} ({definition})")
    
    return text

def professional_question():
    question = "How does untreated chronic anxiety affect one's social interactions?"
    return question
________________________________________
