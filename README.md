# EU AI Act Trustworthiness Model

Replication materials for the paper:

**Conceptual Modelling of EU AI Act towards Trustworthiness and Regulatory Compliance for AI Systems**
Ijeoma Faustina Ekeh, Tolulope Ruth Ogundele, Joy Mugambi, Raimundas Matulevičius
University of Tartu · Hochschule der Bayerischen Wirtschaft

> Funded by the European Union under Grant Agreement No. 101087529.

---
## The Conceptual Model

This file contains the UML class diagram, including all attributes of the conceptual model, and an instantiation example of two requirements.
**[View EU AI Act Trustworthiness Model](https://lucid.app/lucidchart/1336376e-c24b-4537-a8a8-6bcd71fcf566/edit?viewport_loc=-1239%2C-1434%2C6789%2C3573%2C0_0&invitationId=inv_c2146e98-b9df-45e6-9b42-d7959c8af52d)**

## Instantiation Example

**[View Instantiation Example](https://docs.google.com/spreadsheets/d/1MbbeduWqMhBWYfHpvD2xtPMUjGuaaXux/edit?usp=sharing&ouid=106764535231219353686&rtpof=true&sd=true)**

This file demonstrates how the conceptual model is applied to two real high-risk AI systems under the EU AI Act. It contains two sheets:

| Sheet | System | Classification |
|-------|--------|----------------|
| `HireVue AI` | HireVue AI hiring assessment platform (CUSTARD model, RoBERTa-based) | High-risk under Annex III Item 2 (employment AI) |
| `Icare-central Analysis` | iCare Central AI-driven assistive wheelchair navigation system | High-risk under Article 6(1) in conjunction with MDR 2017/745 |

### Sheet Structure

Both sheets share the following columns:

| Column | Description |
|--------|-------------|
| `SystemId` | Unique identifier for the system asset |
| `SystemAssetName` | Name of the assessed system component |
| `System description` | Description of the component's function |
| `Lifecycle` | Lifecycle stage (e.g., deployment, training, monitoring) |
| `ReqId` | Unique requirement identifier |
| `ReqDescription` | Description of the requirement |
| `ReqSource` | EU AI Act article from which the requirement is derived |
| `VerificationMethod` | How compliance is demonstrated (e.g., self assessment) |
| `TrustworthinessPrinciple` | HLEG trustworthiness dimension addressed |
| `AIActRequirement` | Specific EU AI Act article and provision |
| `Technical Measures` | Technical measures implemented to satisfy the requirement |
| `EvidenceId` | Unique identifier for the evidence item |
| `EvidenceRef` | Reference or link to the documentary evidence |

The instantiation covers Articles 9 to 15 and Annex IV of the EU AI Act, based on publicly available technical documentation for each system.

---

## How to Apply the Model to a New System

1. Open `Instantiation Example.xlsx`
2. Add a new sheet for your system following the column structure above
3. For each system asset, define requirements and map them to the corresponding EU AI Act article
4. Record the trustworthiness dimension addressed and the technical measures in place
5. Link each requirement to documentary evidence via `EvidenceRef`

**Article coverage:** The template covers Articles 9 to 15 and Annex IV. Chapter V obligations for General Purpose AI models (Articles 51 to 56) and Article 26 deployer obligations are outside the current scope.

---

## Citation

If you use these materials, please cite:

```bibtex
@inproceedings{ekeh2025euaiact,
  title     = {Conceptual Modelling of EU AI Act towards Trustworthiness
               and Regulatory Compliance for AI Systems},
  author    = {Ekeh, Ijeoma Faustina and Ogundele, Tolulope Ruth
               and Mugambi, Joy and Matulevičius, Raimundas},
  year      = {2025},
  note      = {University of Tartu and Hochschule der Bayerischen Wirtschaft}
}
```

---

## License

This work is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
You are free to share and adapt the materials with appropriate credit.

---

## Acknowledgements

This research was funded by the European Union under Grant Agreement No. 101087529. Views and opinions expressed are those of the authors only and do not necessarily reflect those of the European Union or the European Research Executive Agency.
