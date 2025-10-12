# Experiment

## Experiment Design

We chose to use within-subject design for this experiment so each participant will experience all three music conditions. To control for potential order effects, we will use Latin Square rotation, systematically varying the sequence in which participants encounter each condition. Due to the nature of the strength training exercise, participants will be allowed sufficient rest between sessions to mitigate fatigue effects.

## Pre and Post Questionnaires

The pre and post questionnaires in this study are designed to assess participants' physical readiness and psychological responses to the experimental conditions. The pre-questionnaire is based on the Physical Activity Readiness Questionnaire (PARQ), which evaluates participants' baseline health, fitness, and experience with exercise and technology. The post-questionnaire is adapted from the Intrinsic Motivation Inventory (IMI) and includes items measuring motivation, enjoyment, perceived competence, effort, and exertion following each gameplay session.

## In-Game Performance

During each gameplay session, a range of in-game performance metrics are logged to capture participants' interactions and outcomes. These metrics include time stamps, target and player positions (targetY, playerY), the status of the fishing dot (dotStatus), cumulative score, number of fish caught, whether beat is synchronised (beatOffset), and the weight used during the session.

## Data Analysis

At the start of our experiment, each participant will complete a pre-questionnaire. After each of the three session, they will fill out a post-questionnaire. The collected data will be analyzed using the following statistical tests.

### Friedman Test

#### Description

The Friedman test is a non-parametric statistical test used to detect differences in treatments across multiple test attempts. It is especially suitable for within-subjects designs where each participant experiences all experimental conditions. In this study, the Friedman test is applied to compare motivation and performance scores across the three music conditions: no music, music, and music out of sync with movement. This test does not assume normality and is robust for analyzing questionnaire and behavioral data.

#### Null Hypothesis ($H_0$)

There are no differences in the distributions of motivation or performance scores across the three music conditions. Music does not affect these outcomes.

#### Alternative Hypothesis ($H_1$)

At least one music condition leads to different motivation or performance scores compared to the others.

### Wilcoxon Signed-Rank Test

#### Description

The Wilcoxon signed-rank test is a non-parametric test used to compare two related samples, such as scores from the same participants under two different conditions. In this study, it is used for post-hoc pairwise comparisons between music conditions if the Friedman test indicates a significant effect. The Wilcoxon test is ideal for repeated measures data and does not require the assumption of normality.

#### Null Hypothesis ($H_0$)

There is no difference in motivation or performance scores between the two music conditions being compared.

#### Alternative Hypothesis ($H_1$)

There is a difference in motivation or performance scores between the two music conditions being compared.
