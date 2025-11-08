#InProgress 
- How organs and tissues communicate with each other
- Allows organisms to respond to changes in internal and external stimuli to maintain homeostasis
- Relies on hormonal communication
- Influenced by and influences the [[Nervous System|nervous system]]

```mermaid
graph TD
%% ===== HYPOTHALAMUS =====
H[Hypothalamus]

%% ===== PITUITARY =====
AP[Anterior Pituitary]
PP[Posterior Pituitary]

%% ===== TARGET GLANDS =====
T[Thyroid Gland]
A[Adrenal Cortex]
O[Ovaries]
L[Leydig Cells]
S[Sertoli Cells]
LIV[Liver]
M[Mammary Glands]
AC[Adrenal Cortex]

%% ==== AP HORMONES ====
FSH([FSH])
LH([LH])
ACTH([ACTH])
TSH([TSH])
Pr([Prolactin])
En([Endorphins])
GH([GH])


%% ===== PERIPHERAL HORMONES =====
T3((T₃))
T4((T₄))
CORT((Cortisol))
E((Estrogen))
P((Progesterone))
TST((Testosterone))
GH((GH))
IGF((IGF-1))
PRL((Prolactin))
OX((Oxytocin))
ADH((ADH))
GC((Glucocorticoids))
En((Endorphins))
GH((Growth Hormones))
Som((Somatostatin))


%% ==== PROCESSES ====
OO[/Oogenesis/]
Sp[/Spermatogenesis/]

Ov([Ovulation])


%% ==== HPG Axis ====
H -->|GnRH|AP

AP-->FSH-->S
S -->Sp
AP -->LH-->L
L -->TST

AP -->FSH-->O
AP -->LH-->Ov
O --> E
O --> P

%% ==== HPA Axis ====
H -->|CRF|AP
AP -->|ACTH|AC
AC --> GC

AP -->En
GC -.-xEn

%% ==== HPT Axis ====
H --> |TRH| AP
AP --> |TSH| T
T --> T3
T --> T4
T4 --> T3

%% ==== Prolactin ====
H -->|PIF|AP
AP -->|Prolactin| M

%% ==== Growth Hormone ====
H -->|GHRH|AP
AP -->GH

H -->Som-.-x GH

```


## [[Pituitary Gland]]

The pituitary gland has two lobes: the ***anterior** pituitary* and the ***posterior** pituitary*. How the hypothalamus sends the signal depends on which lobe the axis utilizes. 

### [[Anterior Pituitary]]
The [[Anterior Pituitary|anterior pituitary]] (AP) is made of glandular tissue that can both synthesize and secrete [[Peptide Hormones|peptide hormones]]. The hypothalamus releases ***releasing*** and ***inhibiting*** factors into the ***hypophyseal [[portal system]]***.  
- Hypothalamus sends ==endocrine hormones to anterior pituitary==

#### Axes Involving Anterior Pituitary

- [[Reproductive Axis]]
	- AP hormones: **FSH (Follicle Stimulating Hormone)** and **LH (Lutenizing Hormone)**
- [[HPA Axis]]
- [[Thyroid Axis]]

| Hypothalamic Hormone | AP Hormone | Target Tissue          | Effect          |
| -------------------- | ---------- | ---------------------- | --------------- |
| GnRH                 | FSH        | Ovaries, Sertoli cells |                 |
|                      | LH         |                        |                 |
| CRF                  | ACTH       | Adrenal cortex         | glucocorticoids |
| TRH                  | TSH        |                        |                 |



### [[Posterior Pituitary]]
The [[Posterior Pituitary]] only *stores* hormones that the *hypothalamus produces*. The hypothalamus sends axons down into the posterior pituitary. When depolarized, the posterior pituitary releases the hormones (known as **neurohormones**) from the [[Neuron Structure|axon terminals]]. 













whether the axis uses the [[Anterior Pituitary|anterior pituitary]] or the [[Posterior Pituitary|posterior pituitary]].

