# EDU_GUIDE_ENGINE --- ENGINEERING NOTES

## 1. System Overview (Macro Perspective)

The EDU_GUIDE_ENGINE is a structured instructional reasoning engine
designed to assist teachers and learners by transforming raw knowledge
into teachable structures. Unlike generic assistants, the system
organizes educational workflows around explicit learning artifacts such
as lesson plans, explanation blocks, practice sets, and misconception
tracking.

At the macro level, the engine exists to solve three persistent problems
in education systems:

1.  Knowledge is often presented without structure.
2.  Learning gaps often arise from unaddressed misconceptions.
3.  Teaching workflows require repetitive planning work that can be
    automated.

The engine addresses these by separating governance, schema, commands,
and execution outputs.

Architecture hierarchy:

System Identity → Domain Schema → Command Layer → Execution Layer

This hierarchy ensures policy constraints remain stable while commands
and modules evolve.

------------------------------------------------------------------------

## 2. Design Philosophy

The engine is based on four engineering principles:

Accuracy First -- Educational systems must prioritize correctness over
stylistic fluency.

Structured Reasoning -- Learning improves when information is delivered
through explicit stages: concept introduction → explanation → example →
practice → feedback

Misconception Detection -- Students frequently fail due to incorrect
mental models rather than lack of information.

Teacher Amplification -- The engine multiplies teacher effectiveness
rather than replacing teachers.

------------------------------------------------------------------------

## 3. Core Architectural Components

### System Identity

Defines non‑negotiable behavioral constraints.

Examples: - accuracy over fluency - supportive tone - no fabricated
sources - learner‑level adaptation

### Domain Schema

Defines the data structures used by the engine.

Key objects: LearnerProfile EducatorProfile LessonPlan LearningObjective
ExplanationBlock MisconceptionRecord

Example structure:

LessonPlan topic objectives prerequisite knowledge explanation sequence
examples activities

### Command Layer

Commands act as deterministic entry points.

Examples: /build-lesson /explain-topic /generate-practice
/check-misconceptions /adapt-for-level

### Execution Layer

Produces educational outputs such as:

Explanation Blocks Practice Sets Study Guides Assessment Items Teacher
Planning Notes

------------------------------------------------------------------------

## 4. Misconception Engine

Instead of merely generating explanations, the engine predicts likely
misunderstandings.

Example:

Concept: Fractions Common misconception: larger denominators mean larger
values Correction strategy: visual comparisons

------------------------------------------------------------------------

## 5. Adaptive Difficulty Model

Supported levels:

Beginner Intermediate Advanced Professional

Each level changes vocabulary, abstraction, and explanation depth.

------------------------------------------------------------------------

## 6. Execution Flow

Topic Input → Lesson Plan Generation → Explanation Construction →
Example Generation → Practice Generation → Misconception Analysis →
Feedback Suggestions

------------------------------------------------------------------------

## 7. Safety Boundaries

The engine must:

avoid hallucinated facts refuse academic dishonesty requests maintain
supportive tone label uncertainty

------------------------------------------------------------------------

## 8. System Extensibility

Future modules may include:

Rubric Builder Curriculum Alignment Learning Analytics Test Preparation

------------------------------------------------------------------------

## 9. Macro Value

For educators: reduces planning time For learners: improves clarity For
institutions: enables consistent instructional frameworks
