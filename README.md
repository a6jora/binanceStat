 ## Description

Проект выполняющий следующую задачу:
> Bспользуя фреймворк **Nest js**, соберать логи событий типа **Transfer** по контракту **0x0e09fabb73bd3ade0a17ecc321fd13a19e81ce82** за первую неделю его существования. На основе логов формируется набор адресов, на которых побывал этот токен за первую неделю его существования.

Для доступа к данным **binance** была использована библиотека web3.
Контракт: **0x0e09fabb73bd3ade0a17ecc321fd13a19e81ce82**
Web3 host: https://bsc-dataseed1.defibit.io/

Результатом является set-коллекция **addressSet**, содержащая перечень уникальных адресов, на которых был данный контракт.

## License

Nest is [MIT licensed](https://github.com/nestjs/nest/blob/master/LICENSE).

Web3.js is [Licensed](https://github.com/ChainSafe/web3.js/blob/1.x/LICENSE)
