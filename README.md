# 🧠 MindEase – AI Assistant for Acute Stress Situations

## 📌 Problem
 
Acute stress situation which is referred to stress, is a
sudden reaction following a potentially traumatic
or intensely stressful or emotionally upsetting event
such as a serious injury or accident, the loss of a
loved one or being involved in a natural disaster, or even having a fight with family members
Such events can trigger a wide range of transient
emotional, cognitive, behavioural and somatic
reactions and panic episodes which can happen suddenly and without warning. 
During these moments, individuals might have symptoms of:
- Rapid heartbeat
- Shortness of breath
- Headache or dizziness
- Loss of focus
- Low mood
- Suicidal or self harm ideation 

In high-stress situations, people need immediate, simple, and calming guidance.

Most mental health resources:
- Require appointments
- Are required long term treatment
- Are not optimized for immediate crisis response

There is a need for an AI-powered assistant that provides:
- Instant emotional support
- Short, structured calming interventions
- Clear deep breathing exercise guidance 

- ## 🤖 AI System Design

MindEase is designed as a real-time AI intervention assistant.

The system consists of:

1. Input Analysis Layer  
   - Detects emotional intensity from user text

2. Stress Classification Engine  
   - Categorizes stress into Mild, Moderate, or Severe

3. Response Protocol Generator  
   - Selects appropriate intervention style

4. Safety Monitoring Layer  
   - Detects self-harm or crisis indicators
   - Triggers emergency resource guidance if necessary

The AI adapts tone, response length, and structure depending on detected stress severity.
- Are not optimized for immediate crisis response

## 🔎 Stress-Detection Logic

The assistant categorizes stress emotions based on stress scale level and also based on keywords that user typed and it will then divide into three tiers:

### 🟢 Mild Stress
Keywords:
- stressed
- anxious
- overwhelmed
- sad
- angry
- empty

Response Style:
- Distraction Technique
- Grounding Technique
- Deep breathing exercise technique
- Progressive muscle relaxation exercise 

---

### 🟠 Moderate Stress
Keywords:
- can't handle
- too much
- shaking
- heart racing

Response Style:
- Short sentences
- Immediate grounding technique
- Deep breathing exercise technique 
- Progressive muscle relaxation exercise
- Distraction technique 

---

### 🔴 Severe Stress
Keywords:
- panic attack
- can't breathe
- losing control
- going to die
- want to die 

Response Style:
- Very short instruction 
- 4-4-4 breathing pattern
- 5-4-3-2-1 grounding
- Calm reassurance
- Escalation if needed

- ## 🛡 Safety Framework

MindEase follows responsible AI principles:

- Does not provide medical diagnosis
- Does not replace professional therapy
- Avoids clinical language
- Encourages external support when needed

If self-harm or suicide indicators are detected:
- The assistant provides crisis hotline resources
- Encourages contacting trusted professionals
- Uses supportive, non-judgmental language

Privacy:
- No personal data storage
- No emotional profiling retention

- ## 🧩 Prompt Engineering Architecture

The system prompt defines the AI's personality and response structure.

Core Rules:
- Always validate emotion first
- Keep responses under 80 words during panic
- Use short, clear sentences
- Avoid overwhelming explanations
- Never provide medical claims

Stress Emotion Protocol:
1. Emotional validation
2. Controlled breathing instruction (4 seconds inhale, 4 hold, 4 exhale)
3. Grounding technique (5-4-3-2-1 method)
4. Distraction technique
5. Gentle reassurance
6. Optional support escalation

The assistant dynamically adjusts:
- Sentence length
- Tone intensity
- Instruction pacing
Based on detected stress level.

## 📊 System Flow

User Input  
      ↓  
Emotion Analysis  
      ↓  
Stress Emotion Tier Classification  (Using Stress Scale Level & Keywords)
      ↓  
Response Protocol Selection  
      ↓  
Safety Check  
      ↓  
AI Response Output

