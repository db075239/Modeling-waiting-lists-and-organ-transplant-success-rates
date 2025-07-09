# Modeling Waiting Lists and Organ Transplant Success Rates

This repository focuses on dynamic modeling using AnyLogic to analyze the complexities of kidney transplant waiting lists and the factors influencing transplant success rates in Europe.

## Project Overview

Kidney transplantation is a critical intervention for patients with chronic renal failure, but limited donor availability leads to long waiting lists. This project aims to understand and manage the dynamics of these waiting lists and the impact of various factors on transplant outcomes. We developed two dynamic models in AnyLogic to achieve this:

1. **Patient Flow Model**: This model analyzes changes in the waiting list by tracking patient transitions between different states, such as active waiting, unsuitability, and post-transplant recovery [1].

2. **Donor and Transplant Impact Model**: This model assesses the influence of the number of donors and the number of transplants performed on the length of the waiting list [1]. The mathematical representation for the change in waiting list length (\(\Delta L\)) is given by:

   \[
   \Delta L = \beta \, dD - \gamma \, dT
   \]

   where:  
   - \(L\) is the change in waiting list length  
   - \(D\) represents the change in the number of donors  
   - \(T\) represents the change in the number of transplants  
   - \(\beta\) is the rate of change in the waiting list with respect to the number of donors  
   - \(\gamma\) is the rate of reduction in the waiting list with respect to the number of transplants

Both models are based on mathematical equations and historical data, with simulation results presented through generated graphs [1].

## Key Features and Findings

- **Model 1: Patient Categories and Transitions**  
  Simulates patient movement through categories related to the transplant process, helping visualize how various events (e.g., patient removal, successful transplant) affect the waiting list.

- **Model 2: Donor and Transplant Influence**  
  Quantifies the impact of donor availability and transplant volume on waiting list dynamics.  
  Simulation results indicate that:
  - The number of donors is a crucial factor in managing the kidney transplant waiting list [1].
  - An increased number of available organs leads to more successful transplants and a reduction in the waiting list [1].
  - The number of transplanted patients continuously increases, indicating ongoing transplant activities and successful recipients [1].

## AnyLogic Model Files

*(Placeholder: Your AnyLogic model files will be placed here once they are available.)*  

Once you receive the AnyLogic model files (typically `.alp` files), please place them in this repository.

## How to Run the Models (Instructions for AnyLogic)

To open and run the models:

1. **Install AnyLogic**: Ensure AnyLogic software is installed on your machine.  
2. **Clone Repository**: Clone this repository locally.  
3. **Open AnyLogic**: Launch AnyLogic.  
4. **Open Project**: Navigate to `File > Open`, then select the `.alp` file(s) in the cloned directory.  
5. **Run Simulation**: Click the green "Run" button in the toolbar to start the simulation.

## Conclusion

Simulation results underscore the critical role of donor numbers in effectively managing kidney transplant waiting lists. Higher organ availability could significantly reduce waiting times and improve patient outcomes. Future work may explore additional factors such as patient health deterioration on the list and impacts of different organ allocation policies.

---

### References

[1] David Blazheski, Teodora Trajkova, Ivana Kerkez, *Faculty of Electrical Engineering, I year MAG, Specialization: Automation and Informatics*.
