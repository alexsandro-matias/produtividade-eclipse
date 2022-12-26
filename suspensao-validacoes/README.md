# Suspensão de Validações
O Eclipse, por padrão (default), vem configurado para realizar validações em arquivos das mais diversas extensões (formatos), como **.xml** e **.json**, por exemplo, assim como para Framewoks. Desta forma, essas verificações consomem recursos para serem feitos, recursos estes que, dependendo do uso, podem ser suprimidos, deixando o IDE mais performático.

Para desabilitar estas validações, iremos em ``Window -> Preferences``. Depois na busca digite **Validation**. Selecione a **Validation e Resolution** e desmarque ``Enable Validation``.

No caso do Eclipse na versão EE (Enterprise Edition) outras validações podem ser desfeitas indo também em ``Window -> Preferences -> Validation``. Então, marque o checkbox ``Suspend all validators``.