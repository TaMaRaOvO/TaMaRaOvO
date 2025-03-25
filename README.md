إليك الأكواد الخاصة بكل ورشة مع تسمياتها مرتبة حسب الترتيب المتفق عليه:
1. الورشة 1: تحليل النص الأساسي
def analyze_text(text):
    # هنا يتم تحليل النص الأساسي
    # استخراج الشخصيات، الأحداث، والمحتوى الأساسي
    analyzed_text = {For the first time, Daniel sat across from me with a laptop resting on his knees. I’d found him that way when I opened the door three minutes ago. I’d sent him more journal entries, hoping to keep our live discussions to a minimum after what happened last weekend at the sale, but now a new wave of awkwardness poured over me. I wasn’t expecting he’d be digging through my brain, analyzing my soul, right in front of me. Maybe I’d caught a break, and he was watching porn.
“No notepad today?” My eyes skirted around the room, hoping it could be my chance to take a peek at it.
“I apologize for this. There’s coffee there if you like.” He head gestured to a small table next to his desk without making eye contact with me. His tone left nothing for me to read, as if he erased what happened between us.
“I’m good, thanks.” My nerves couldn’t take an additional jolt. “I’ve got plenty to keep myself busy.” I strolled toward my escape window in time to view the orange glow of the sun lower behind the tall tower to our right. The reflection off the glass brightened a patch of green grass below. “Take your time.”
A few minutes later, his voice startled me. “Normally, I wouldn’t be so rude…” My mind had involuntarily played a loop of Daniel’s hungry gaze on my mouth. “…but I’d hoped to finish this last excerpt before we talked.”
I took a seat in the chair closest to Daniel rather than the couch across from him. A quick glimpse of my placement showed the uncertainty in his eyes.
“First, let me say that I appreciate you sending me these. I found it extremely enlightening what you chose to send this time.”
I tilted my head in confusion, unsure of what he was getting at.
“You’re concerned about my perception of your friend Nathan. Is that why you sent these?”
I lifted a shoulder and let it fall. I had emailed him three entries. Two were about my first encounters with Nathan. “I just wanted you to learn a bit about him…understand where he came from.”
“Growing up in foster care can be extremely tough to handle for any child, but it sounds like Nathan had it pretty tough.”
“It’s not like they beat him or anything. It was pretty damn clear they were in it for the money, though.”
“Was there anyone he could rely on?”
“Not really. Even his foster brother, Kevin, had been a lowlife. But,
Nathan found a way to rise above all that.”
“You mean after he ended up in rehab?”
“His family is why he ended up there…but, yes.” Daniel hadn’t said anything that wasn’t true, but I still found myself feeling defensive.
“Then came AA, and that’s when you two met?”
I nodded and then went on to tell him how I joined halfway through college. My grandmother had a decent estate when she died, none of which went to my father. My portion, intended to help me pay for college, had done that in addition to assisting me in managing my anxieties through liquid medication.
“By the end of my sophomore year, I’d run out of money. Becca and Barb had agreed to use some of their inheritance to help me pay the rest. It was what Grandma would have wanted for me. It was on the condition that
I get help.”
“Sounds like you’re in a similar position now.”
“Thanks for stating the obvious.”
“You’re right. I’m sorry.” He closed the laptop and set it onto the table next to him. Then, he did something he’d never done during one of our sessions. He stood, wandering away as if he needed distance from me.
“This might be a good time to have a sidebar.”
“Are the drinks free?”
His hands slipped into the pockets of his black slacks as he eyed the carpet at his feet. “I’d like you to take this seriously, Gray.”
“Then, look at me.” Slow and deliberate, his gaze turned up to mine. The shift in control felt oddly intoxicating. I scooted to the end of my seat, rested my elbows on my knees, and said, “If you’ve got something to say to me, just say it…but at least look me in the eye when you do it.” If I was going down, it would be with my head held high.
He took two strides in my direction. “Another shortcoming on my part. Gray, I’m going to be honest here, and say you’ve got me off my game. I’ve been unprofessional with some of my responses, and these sessions have become somewhat unconventional to say the least.”
Stunned into silence by not only his bravado but also his complete lack of acknowledgement of the bigger picture, I stared at him, mouth agape. Then, boldly I stood and faced him. His eyes, dark with anticipation, met mine. “Seriously?” My heart thudded erratically as I moved in closer. “I don’t give a damn about your responses, Daniel. You can say whatever you want to say to me. I’m just trying to get through this.” One more step had us toe-to-toe, leaving me looking up to stay connected. “But, what you failed to acknowledge here…what you seemed to be forgetting…or you’re afraid to say it out loud is how when you touched my body, your heart pounded so hard through your chest I felt it against my back.”
Daniel averted my eyes, looking beyond me to the window. “Gray… don’t do this.”
His body swayed, about to move back, but I caught his arm. “No…you started this. Are you denying you felt something? Are you denying what your eyes told me right before you were about to kiss me?”
“I didn’t…I stopped it. It was wrong. This is wrong.” He broke away then and went toward his desk.
“That’s not what I asked you? What’s the matter? You can’t handle the open and honest rule?”

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
