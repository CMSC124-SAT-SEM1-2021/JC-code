
<syntax> -> begin <block> end
<block> -> <assign>; | <assign>; <block>
<assign> -> <var> = <expr>
<expr> -> <var> + <expr> | <var> * <expr> | ( <expr> ) | <var>
<var> -> A | B | C