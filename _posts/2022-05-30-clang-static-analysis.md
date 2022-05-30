

Static analysis -- for Cross TU work 
If you want to develop a thing to work with a single file (even header) -- use ast-dump etc.
If you want to edit a file, see an example here clang-extra-tools/clang-apply-replacements. It deals with FileManager, SourceManager, down to Rewriter class.
