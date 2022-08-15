# FunctionalHarmony
An Ontology for Functional Harmonic Analysis of Chord Progressions

Each chord progression should be represented as an RDF knowledge graph. Consecutive chords are connected by fho:hasNext edges, and for each chord in the progression we assert its chord type by adding triples of the form ⟨chrd_1⟩ ⟨rdf:Type⟩ ⟨fho:Cmaj9⟩. The last chord should be connected to ⟨chrd_x⟩ ⟨rdf:Type⟩ ⟨fho:NoChord⟩.
