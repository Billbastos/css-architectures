# Atomic design
- 5 Principles:
  1. Atom ( html tag )
  2. Molecule ( group of html tags / atoms ul>li>a )
  3. Organism ( group of molecules header>form>input^ul>li ) in this case the header tag is the Organism that contains two molecules form and ul.
  4. Template ( group of Organisms like wireframe - abstract )
  5. Page ( Instance of Template that implements the real content - concrete )