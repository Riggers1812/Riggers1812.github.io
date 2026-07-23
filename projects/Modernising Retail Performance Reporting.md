# Project: Modernising Retail Performance Reporting

## The Challenge
Performance targets are only useful if they can be trusted, understood and analysed consistently.
In this project, branch targets existed outside the core analytics architecture and were primarily accessible through proxy metrics. While reporting was possible, the underlying approach created unnecessary complexity and limited the flexibility of downstream analysis.
The challenge was not simply to build another report. The real challenge was to create a stronger foundation that would allow targets to become part of the wider analytics ecosystem.

## My Role
I was responsible for designing and implementing the modelling changes required to integrate target data into the broader reporting framework.
This involved understanding the existing architecture, identifying where targets sat within the model, refactoring supporting logic, and ensuring the final solution aligned with established modelling standards.

## My Approach
Rather than adding more reporting logic on top of existing workarounds, I focused on addressing the problem at the modelling layer.
I integrated branch targets into the comprehensive model, built a new construct layer to support analysis, and refactored currency logic to bring it in line with wider architectural standards.
Alongside the modelling work, I also supported trade review reporting requirements, reporting scheduling improvements, and the development of store-level target reporting.
Key areas of work included:

- Integrating branch targets into core data models
- Developing a new construct layer
- Refactoring currency calculations and logic
- Supporting performance review reporting
- Improving reporting automation and scheduling
- Enabling consistent target analysis across locations

## Outcome
The result was a more scalable and maintainable reporting foundation.
Target data became independently queryable, reducing reliance on proxy metrics and enabling more flexible analysis. Reporting became more consistent across retail outputs, while the underlying model became simpler to understand and maintain.
The work also established a platform for future reporting initiatives without introducing additional technical debt.
Key outcomes included:

- Improved consistency across reporting outputs
- Reduced modelling complexity
- Better branch-level performance analysis
- Stronger alignment with modelling standards
- A scalable foundation for future development

## What I Learned
This project reinforced a lesson that appears repeatedly in analytics work:

The most valuable reporting improvements often come from strengthening the model rather than adding another layer of reporting logic.


Investing time in the foundation created benefits that extended far beyond a single report and improved every downstream use of the data.
Technologies
