<template>
    <LecturePage 
        title="Energy Quantization"
        :text="ptext"
        imgsrc ="../images/qubit.png"
        imgalt="qubit">
    </LecturePage>
</template>

<script>
    export default {
        data () {
            return {
                ptext: ["When a classical bit is measured, it returns a value of either 0 or 1, and nothing in between.  A similar phenomenon occurs in quantum systems.  When measuring the energy of a ball rolling down a hill, one could expect to get any number of values for the energy of that ball, ranging from 0, if the ball is still, to increasingly large numbers if the ball is moving faster.  However, the same is not true in quantum systems.  The measurement of the energy of an electron can only yield discrete values, rather than a continuous range of values.", "Moreover, electrons can be promoted from a given energy level to a higher energy level if it can absorb the amount of energy corresponding to the gap between the two levels.  For example, if an electron is in the ground state and it absorbs a photon of sufficient energy, it can be elevated to the first excited state.  It is clear that this property is incredibly useful for the development of qubits.  If we can isolate the first two energy levels of a system, they can represent the |0> and  |1> states found in classical bits.  And, we can use photons of specific energies to change the state of an electron from one state to the other.", "However, many challenges come with manipulating quantum systems.  First of all, natural atoms come preprogrammed with specific energy levels and energy spacing which cannot be dictated by the engineer.  They are also difficult, and nearly impossible, to manipulate and integrate into the framework of a computer.  For this reason, scientists often look towards creating synthetic atoms, which exhibit the quantum mechanical properties of normal atoms, but are customizable because they are manufactured from the ground up.  Larger systems with observable quantum mechanical properties are hard to come by, but are made possible by the existence of superconductors."]
            }
        }
    }
</script>
