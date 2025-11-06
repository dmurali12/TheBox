```mermaid
graph TD
H[Hypothalamus]
AP[Anterior Pituitary]
O[Ovaries]
L[Leydig Cells]
S[Sertoli Cells]

H--> |GnRH| AP
AP -->|FSH - female| O
AP --> |FSH- male| S
AP --> |LH - female| O
AP --> |LH - male| L

```

1. GnRH expressing neurons in the [[hypothalamus]] releases [[Gonadotropin Releasing Hormone (GnRH)]]. 
2. The [[anterior pituitary]], in response, releases [[Follicle Stimulating Hormone]] and [[Lutenizing Hormone]]

## Reproductive Axis in Females

The ovarian and uterine cycles in females occur concurrently. We'll first talk about each separately and then put it together. 
### Ovarian Cycle
1. **Follicular Phase**: Hypothalamus releases **GnRH**, so AP releases *small* amounts of **FSH** and **LH**
	- FSH and LH act on the **ovaries** and causes it to release **estrogens**. 
	- Low levels of estrogen ***inhibits*** GnRH production
	- As estrogen levels rise, 

GRAPH HERE OF JUST FOLLICULAR PHASE

2. **Ovulation**: 

```chart
type: line
labels: [0,5,10,14,20,28]
series:
  - title: FSH
    color: deeppink
    data: [1,1.5,1.8,2.2,1.4,1]
  - title: LH
    color: dodgerblue
    data: [1,1.3,2.2,4.5,1.5,1]
  - title: Estrogen
    color: purple
    data: [1,2,3,2.5,4,1]
  - title: Progesterone
    color: seagreen
    data: [0.5,0.5,1,2,4.5,3]
options:
  scales:
    x:
      title:
        display: true
        text: "Day of cycle"
    y:
      title:
        display: false
        
	elements:
		line: 
			tension: 0.5
```
