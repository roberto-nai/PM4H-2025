# Leveraging Large Language Models on Healthcare Event Logs for Predictive Process Monitoring

This repository contains materials related to the scientific article **"Leveraging Large Language Models on Healthcare Event Logs for Predictive Process Monitoring"**.  

Authors: Vladimiro Lovera Rulfi, Roberto Nai, Emilio Sulis, Luigi Di Caro, Laura Genga, Adriana Boccuzzi.  

## Abstract

Predicting the outcomes of ongoing process instances remains a central challenge in the field of Predictive Process Monitoring. While deep learning techniques have recently demonstrated strong performance in tackling this task, the emergence of Large Language Models (LLMs) has opened new opportunities for innovation.  This research explores the expressive power of LLMs and the richness of textual representations to enhance predictive capabilities. 
Our method transforms structured event log data into coherent, narrative-style text descriptions. These “semantic stories” capture the context and evolution of each process instance, constructed using domain-specific templates that reflect real-world healthcare workflows. Leveraging a pre-trained LLM, we fine-tune the model using historical data from an Emergency Department in the Turin area, enabling it to learn patterns associated with different process outcomes. 
By reframing the prediction task as a text-based learning problem, this approach allows the LLM to interpret process histories in a more human-like, contextualised manner.

## Repository Structure

- `images/` — Figures and diagrams referenced in the article.
- `README.md` — This file.


## Connected repositories
- Event Log enrichment: [https://github.com/roberto-nai/HOSPITAL-EVENTLOG-ENRICHMENT](https://github.com/roberto-nai/HOSPITAL-EVENTLOG-ENRICHMENT)
- LUPIN-fork: [https://github.com/roberto-nai/LUPIN-fork](https://github.com/roberto-nai/LUPIN-fork)

## Citation


## Contact

For questions or collaborations, please contact: [vladimiro.loverarulfi@unito.it](vladimiro.loverarulfi@unito.it), [roberto.nai@unito.it](mailto:roberto.nai@unito.it), [emilio.sulis@unito.it](mailto:emilio.suli@unito.it)
