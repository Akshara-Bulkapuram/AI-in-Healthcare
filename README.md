
# Intelligent Prescription Error Detection System

## Overview

Inaccurate prescriptions can lead to severe health consequences and increased healthcare costs. This project presents an **Intelligent Prescription Error Detection System** that uses **Artificial Intelligence (AI)** and **blockchain technologies** to enhance the accuracy and security of medical prescriptions.

This system integrates Optical Character Recognition (OCR), Natural Language Processing (NLP), Named Entity Recognition (NER), and blockchain to provide a robust, secure, and scalable solution for identifying and mitigating prescription errors.

## Key Features

- **Prescription Text Extraction**  
  Utilizes **OCR techniques** to extract text from prescription images.  
- **NLP and NER Analysis**  
  Identifies critical entities such as:
  - Drug names
  - Diseases
  - Symptoms  
  Powered by **Gemini API** for Named Entity Recognition (NER).  
- **Drug-Disease Validation**  
  - Maps drug brand names to their generic equivalents using **RxNorm**.  
  - Validates drug-disease appropriateness using **fuzzy logic** and **RxNorm** data.  
  - Categorizes prescriptions as **valid** or **erroneous**.  
- **Data Security with Blockchain**  
  - Prescription data is securely stored using **IPFS (InterPlanetary File System)**.  
  - Employs blockchain for data integrity and decentralized access.  
- **Decentralized Front End**  
  - Provides user authentication through blockchain wallets.  
  - Accessible for both doctors and patients.

## Workflow

1. **Input:** Image of a prescription.  
2. **OCR:** Text extraction.  
3. **NLP/NER:** Identification of entities like drug names, diseases, and symptoms.  
4. **Validation:** Drug-disease pairing validation using RxNorm and fuzzy logic.  
5. **Categorization:** Prescription marked as valid or erroneous.  
6. **Data Security:** Data stored on IPFS and secured with blockchain.  
7. **User Access:** Decentralized front end for secure interactions.

## Technologies Used

- **Artificial Intelligence**  
  - OCR: Text extraction  
  - NLP and NER: Entity recognition (Gemini API)  
- **RxNorm:** Drug-disease data mapping  
- **Blockchain and IPFS:** Data integrity and security  
- **Decentralized Front End:** Blockchain wallet authentication  

## Goals

- Enhance prescription accuracy and reduce health risks.  
- Provide a secure and scalable solution for prescription error detection.  
- Safeguard patient and doctor data using blockchain technology.

## How to Use

1. Upload an image of a prescription through the decentralized front end.  
2. Let the system analyze the prescription using AI techniques.  
3. Alert is sent to doctor for corrections (if needed).  

## Contributions

Contributions are welcome! Please submit a pull request or open an issue for discussions.  



