$$\huge
\frac{ \partial^2 \vec{E} }{ \partial t^2 } =\frac{1}{\epsilon_{0}\mu_{0}}\nabla \vec{E} \qquad  \frac{ \partial^2 \vec{B} }{ \partial t^2 } =\frac{1}{\epsilon_{0}\mu_{0}}\nabla \vec{B}
$$
$$\huge
\vec{E}(\vec{r},t)=\vec{E}_{0}\sin(\vec{k}\vec{r}-\omega t)
$$
k := [[Wellenzahl]]

---
### Herleitung
Geltende Wellengleichungen im Vakuum
$$
div \vec{E}=0 \qquad rot\vec{E}=-\frac{ \partial B }{ \partial t } 
$$
$$
div\vec{B}=0\qquad rot\vec{B}=\epsilon_{0}\mu_{0}\frac{ \partial \vec{E} }{ \partial t } 
$$
$$
rot(rot(\vec{E}))=rot\left( -\frac{ \partial \vec{B} }{ \partial t }  \right)=- \frac{ \partial  }{ \partial t }  rot\vec{B}=-\epsilon_{0}\mu_{0}\frac{ \partial ^2\vec{E} }{ \partial t^2 } 
$$
und da $div\vec{E}=0$
$$
rot(rot(\vec{E}))=-\nabla \vec{E}
$$
