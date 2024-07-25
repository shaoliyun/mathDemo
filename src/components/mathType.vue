<template>
  <div style="width: 800px;">
    <hr/>

    <div style="flex-direction: row;">
      <p style="text-align: left;">Alice</p>
      <p style="text-align: right;">BOB</p>
    </div>

    <hr/>
    <hr/>
    <p style="text-align: left;">KEY GENERATION</p>
    <hr/>
    <div style="text-align: left; width: 50px;">
      <katex-element  expression="\\ \mathrm{Choose~a~linear~code~}\mathcal{C}\subseteq\mathbb{F}_q^n\mathrm{~of~dimension~}k\\\mathrm{and~error~correction~capacity~}t."/>
      <katex-element  expression="\\ \mathrm{~Let~}\mathbf{G}\mathrm{~be~a}\end{array} k\times n\text{ generator matrix of }\mathcal{C}."/>
      <katex-element  expression="\\ Let \ \bf{G} \ be \ a \ k \times n  \ generator \ matrix \ of \ \cal{C} ."/>
      <katex-element  expression="\\ \begin{array}{l}\text{Choose randomly }\mathbf{S}\in\mathrm{GL}_k(\mathbb{F}_q)\text{ and an }n\times n\\\text{permutation matrix }\mathbf{P}.\text{ Compute }\mathbf{G}^{\prime}=\mathbf{SGP}.\end{array}"/>
      <katex-element  expression="\\ \begin{array}{l}\text{The public key is given by} \ \mathcal{P} = (t,\mathbf{G}') \mathrm{and}\\\mathcal{S}=(\mathbf{G},\mathbf{S},\mathbf{P})\end{array}"/>
    </div>

    <div>
      <katex-element  expression="\\ \xrightarrow{\mathcal{P}}"/>
    </div>
    
    <div style="text-align: right;">
      <hr/>
      <p>ENCRYPTION</p>
      <hr/>
    </div>

    

    <div style="text-align: right; flex-direction: row;">
      <katex-element  expression="\\ \begin{array}{c}\text{Choose a message m}\in\mathbb{F}_q^k\text{ and a random}\\\text{error vector e}\in\mathbb{F}_q^n\text{ of weight at most }t\end{array} "/>
      
    </div>

    <div style="text-align: right;">
      <katex-element  expression="\\ \text{Encrypt the message c=mG'+e} \ \text{Encrypt the message c=mG'+e}"/>
    </div>
    
    <div>
      <p></p>
    </div>

    <div>
      <katex-element  expression="\\ \xleftarrow{\mathrm{c}}"/>
    </div>

    <hr/>
    <div style="text-align: left; width: 800px;">
      <p>DECRYPTION</p>
    </div>

    <hr/>

    <div style="text-align: left; width: 50px;">
      <katex-element  expression="\\ \mathrm{Decrypt~the~cipher,~by~decoding~cP^{-1}~=}\\\mathrm{mSG+eP^{-1}~to~get~mS,~and~finally~recover}"/>
      <katex-element  expression="\\ \mathrm{the~message~as~}\mathbf{m}=(\mathbf{m}\mathbf{S})\mathbf{S}^{-1}"/>
    </div>

    <hr/>

      
    
  </div>
    
</template>

<script>

export default{
  name:'mathType',
}
</script>

<style>
</style>