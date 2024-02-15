Как видно, снаружи пропсы передаются как атрибуты в HTML, которые внутри компонента доступны из объекта props. Причём такая передача входных данных для вас уже должна быть не в новинку. Встроенные компоненты точно так же принимают на вход пропсы, такие как className и другие.

const vdom = (
  <div className="row">
    <div className="col-6">
      <HelloMessage name="Kate" />
    </div>
    <div className="col-6">
      <HelloMessage name="Mark" />
    </div>
  </div>
);
