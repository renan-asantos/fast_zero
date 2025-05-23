Correcoes aula 4

Segurança: ORMs lidam geralmente com escapagem de consultas e para prevenir injeções SQL, um tipo comum de vulnerabilidade de segurança.
> Texto estranho

Isso está alinhado com a metodologia dos 12 fatores, um conjunto de melhores práticas para desenvolvimento de aplicações modernas. O terceiro fator, "Config", afirma que as configurações que variam entre os ambientes devem ser armazenadas no ambiente e não no código.
> Link pra 12 fatores, além de mover o "caso queira saber mais sobre 12 fatores" pra debaixo desse parágrafo

Configurações de ambiente e os 12 fatores
> Revisar essa seção toda

Além do Core e do ORM, o SQLAlchemy conta com outros componentes cruciais que serão foco desta aula, a Engine e a Session:
> Colocar : a Engine e a Session.

with Session(engine) as session:
> comentário nisso mal formatado



