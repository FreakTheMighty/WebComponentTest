Query results in null
=====================

When I query for a dom element in the main funciton I get a null back.

Looking at the autogenerated code's bootstrapping I see that main function is
called before init_autogenerated, flipping these fixes the problem.  Is this by design?
